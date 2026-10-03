# Portfolio — Léa Tramati

## Mettre le site en ligne (GitHub Pages)
1. Sur github.com, créer un dépôt public nommé `portfolio`.
2. « Add file » → « Upload files » : déposer `index.html` et les dossiers `vignettes` et `photos`.
3. Settings → Pages → Source : « Deploy from a branch », branche `main`, dossier `/ (root)`.
4. Après une minute, le site est à l'adresse https://lea-tramati.github.io/portfolio/
   (c'est l'adresse encodée dans le QR code ; si le dépôt a un autre nom,
   changer `SITE_URL` en haut du script dans index.html).

## Le jour de l'expo
- Ouvrir https://lea-tramati.github.io/portfolio/#expo
  → démo automatique après 30 s sans activité, les projets s'ouvrent dans le même onglet.
- Cliquer l'icône en points en haut à droite pour passer en plein écran.
- Le dossier `photos` contient les photos de la soirée potluck (ambiance + galerie).
- Ouvrir Intrusion une première fois avant l'arrivée du public (le jeu pèse ~40 Mo).
- Sans internet : ouvrir directement index.html depuis ce dossier
  (les vignettes et le teaser sont inclus ; seuls les polices, le QR code et les liens externes ont besoin du réseau).

## Lien direct vers un projet
…/portfolio/#intrusion, #feed-your-head, #robert-wun, #apperture, #kisd-spaces

## Réglages en haut du script (index.html)
- `PORTRAIT` : chemin d'une photo de vous pour « À propos » (ex. "vignettes/portrait.jpg").
- `CONTACT` : { label: "@votre.insta", href: "https://instagram.com/votre.insta" } pour afficher un contact.
- Images de processus : ajouter `process: ["vignettes/croquis.jpg"]` à un projet.

## Vues
- …/portfolio/ : champ d'images relié par le fil rouge
- …/portfolio/#index : grille de tous les projets et des photos

## À imprimer
- `../carte-qr-portfolio.pdf` : carton A5 avec le QR code, à poser à côté de l'écran.
