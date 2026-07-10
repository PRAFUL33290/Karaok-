# Karaoké Familles – GameClub

Playlist karaoké de 50 titres français pour animer un karaoké familial (enfants + parents), avec un suivi des chansons déjà préparées par les enfants.

## Pages

- **`index.html`** — la playlist complète : 50 titres classés par ambiance (fête, variété française, duos, années 80-90, chansons enfants), le programme GameClub 17h00–17h45, et des suggestions de playlists YouTube/Karafun.
- **`preparation.html`** — une case à cocher par chanson pour suivre celles déjà préparées par les enfants. La progression est enregistrée automatiquement dans le navigateur (`localStorage`), avec un bouton pour tout réinitialiser.

## Développement

Pages statiques, aucune dépendance : ouvrir `index.html` dans un navigateur, ou servir le dossier avec un serveur statique (`python3 -m http.server`).
