# Excellence TV

Site public d'Excellence TV, lecteur IPTV pour Windows. L'appli ne fournit aucun contenu : chacun ajoute sa propre source.

| Fichier | Rôle |
|---|---|
| `index.html` | Politique de confidentialité (fr / en), adresse donnée au Microsoft Store |
| `demo.m3u` | Liste de flux de test publics (Mux, Apple), pour les testeurs du Store |
| `config.json` | Réglages lus par l'appli au démarrage : clés de service de l'appli (sous-titres, affiches). Une clé changée ici est prise par toutes les applis, sans mise à jour |
| `licenses.json` | Accès de l'édition payante : seulement les empreintes (identifiant + clé) et leur état (actif, en attente du paiement, révoqué). Écrit par `npm run licence` |
| `activer.html` | Page d'un lien d'activation (QR code, message) : affiche l'identifiant et la clé, qui restent dans le fragment de l'adresse, et ouvre l'appli |

Assistance : onglet [Issues](https://github.com/jaimelavittel/excellence-tv/issues).

Ce dépôt est publié depuis le projet de l'appli (`store/site/`, `npm run site:publish`) : modifier les fichiers là-bas.
