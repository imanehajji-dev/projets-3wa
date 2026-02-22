📁 Contenu du dossier
- index.html : structure HTML du projet
- scss/_variables.scss : couleurs, polices, espacements (margin / padding)
- scss/_base.scss : généralités du projet (html, body, titres, ...)
- scss/_layout.scss : styles des éléments du layout (header, nav, containers, footer)
- scss/_components.scss : styles des éléments spécifiques qui composent les pages
- scss/index.scss : fichier principal qui importe les autres
- css/ : contiendra le css généré par l'outil de compilation SASS. Aucun code manuel ne doit s'y trouver.

🔎 Spécificités
- Couleur principale : #6f4e37
- Couleur secondaire : #bfa58a
- Couleur claire : #fdfaf6
- Couleur foncée : #1c1c1c
- Police par défaut : Georgia (serif)
- Unité d'espacement petite: 0.5rem
- Unité d'espacement moyenne: 1rem
- Unité d'espacement grande: 2rem
- Arrondis : 0.5rem
- Largeur maximale du contenu principal : 1200px
- Points de rupture : tablette 680px, bureau 1200px

- Page accueil : la largeur maximale de la partie "Bienvenue au Café du Coin" est de 600px.
- Les éléments de la galerie, les tarifs et les articles sont dans un container fluide (cad sans point de rupture).
Les éléments ont une largeur minimale de 180px ou 100%.

✅ Critères de réussite
- Utilisation de variables dans un fichier dédié
- Découpage des éléments dans les différents fichiers : base / layout / components
- Code structuré avec les imbrications
- Le fichier final CSS est compilé et fonctionnel
- Le code SASS est lisible, propre, et cohérent
