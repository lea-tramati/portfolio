# Portfolio — Léa Tramati

## Mettre le site en ligne (GitHub Pages)
1. Sur github.com, créer un dépôt public nommé `portfolio`.
2. « Add file » → « Upload files » : déposer `index.html` et les dossiers `vignettes` et `photos`.
3. Settings → Pages → Source : « Deploy from a branch », branche `main`, dossier `/ (root)`.
4. Après une minute, le site est à l'adresse https://lea-tramati.github.io/portfolio/
   (c'est l'adresse encodée dans le QR code ; si le dépôt a un autre nom,
   changer `SITE_URL` en haut du script dans index.html).

## Le jour de l'expo
- Double-cliquer `../Lancer-portfolio-expo.bat` : le site s'ouvre en plein écran (mode kiosque) en mode expo, et l'ordinateur ne se met plus en veille. Quitter : Alt + F4.
- Sans internet : `../Lancer-portfolio-hors-ligne.bat` (utilise ce dossier).
- Après l'expo : `../Retablir-veille.bat` remet la mise en veille.
- Avant l'arrivée du public : activer « Ne pas déranger » dans Windows (notifications), ouvrir Intrusion une fois, brancher un casque pour le son.
- Imprimer `../carte-qr-portfolio.pdf` (A5) et `../cartels-portfolio.pdf` (A4, 4 cartels A6 par page, à découper).

## Lien direct vers un projet
…/portfolio/#intrusion, #feed-your-head, #robert-wun, #apperture, #kisd-spaces

## Réglages en haut du script (index.html)
- `PORTRAIT` : chemin d'une photo de vous pour « À propos » (ex. "vignettes/portrait.webp").
- `CONTACT` : { label: "@votre.insta", href: "https://instagram.com/votre.insta" } pour afficher un contact.
- Images de processus : ajouter `process: ["vignettes/croquis.jpg"]` à un projet.

## Accessibilité
- Clavier : ← → (ou les flèches à l'écran) pour passer d'un projet à l'autre, Entrée pour ouvrir, Échap pour fermer, Tab pour parcourir les boutons.
- Bouton « Pause » en haut : arrête toutes les animations (mémorisé pour la visite suivante).
- Lecteurs d'écran : chaque projet et chaque image ont une description en FR/EN/DE (champ `alt` des projets).

## À imprimer
- `../carte-qr-portfolio.pdf` : carton A5 avec le QR code, à poser à côté de l'écran.
