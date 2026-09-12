# Karamoe Group Viewer

Visualiseur de playlists **Karaoke Mugen** (`.kmplaylist`) pensé pour préparer une soirée à plusieurs : temps de passage par participant, répartition de la durée, recherche, filtres par tag.

Aucune installation, aucun serveur : `index.html` est une page autonome, à ouvrir directement dans un navigateur ou à héberger tel quel (GitHub Pages, etc.).

## Fonctionnalités

- Chargement d'un fichier `.kmplaylist` par glisser-déposer ou sélecteur de fichier
- Titre, description et statistiques globales de la playlist (durée totale, nb de karaokés, participants actifs)
- Temps théorique total et nombre d'utilisateurs théorique configurables, avec recalcul en direct
- Recherche par titre ou artiste (insensible aux accents)
- Filtres par tag (type de chanson, tags "misc") en un clic
- Tri des participants par durée, nombre de karaokés ou nom (appliqué à la fois à la liste et aux cartes détaillées)
- Détail par participant, repliable, avec statut visuel (OK / limite / dépassement / inactif) et barre de progression
- Répartition de la durée d'un participant entre plusieurs personnes (plusieurs répartitions simultanées possibles)
- Ajout de karaokés fictifs (titre, artiste, durée, participant) pour préparer un complément qui sera importé plus tard, sans attendre le fichier final
- Export du résumé (copie dans le presse-papier) pour le partager ailleurs (Discord, etc.)
- Thème clair / sombre (suit le système, ou choix manuel mémorisé)
- Réglages mémorisés d'une session à l'autre (temps théorique, tri, thème)

## Utilisation

Ouvrez `index.html` dans un navigateur, puis glissez-déposez votre export `.kmplaylist` depuis Karaoke Mugen.
