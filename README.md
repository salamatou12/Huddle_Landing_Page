
# Huddle — Landing Page

Description
- Page de présentation statique (HTML + CSS) responsive.
- Conçue pour un héros visuel, une section produit/illustration et un footer riche en informations.

Prérequis
- Navigateur moderne (Chrome, Firefox, Safari).
- Optionnel : VS Code + extension Live Server pour développement local.

Installation & lancement
1. Cloner ou copier le dossier du projet sur ta machine.
2. Ouvrir `indx.html` (ou `index.html`) dans le navigateur, ou lancer Live Server depuis VS Code.
3. Vérifier que les assets (SVG/PNG) référencés dans le HTML existent au même emplacement que les chemins indiqués.

Structure du projet
- indx.html (fichier HTML principal)
- style.css (styles principaux, breakpoints inclus)
- /assets ou /images (dossier attendu pour : logo.svg, bg-hero-desktop.svg, bg-hero-mobile.svg, illustration-*.svg, bottom-logo.svg, etc.)
- README.md (ce fichier)

Points importants à vérifier
- Importer la police Poppins via Google Fonts dans le <head> si nécessaire :
  <link href="https://fonts.googleapis.com/css2?family=Poppins&display=swap" rel="stylesheet">
- Corriger les éléments non responsives : éviter les largeurs fixes très grandes (ex. `width: 80rem`) et les positions absolues avec valeurs extrêmes (`.bloc3`).
- Sémantique : utiliser header, main, section pour améliorer l'accessibilité.
- Accessibilité : vérifier contraste, attributs alt sur les images et rôle ARIA si nécessaire.
- Performance : optimiser et mettre en cache les SVG/PNG ; ajouter loading="lazy" pour images secondaires.

Bonnes pratiques recommandées
- Utiliser des unités relatives (% / vw / rem) pour la mise en page.
- Tester sur plusieurs tailles d'écran et mobile.
- Ajouter validation HTML/CSS et un test d’accessibilité (Lighthouse).

Contribution
- Faire une branche par feature, ouvrir une pull request décrivant les changements.
- Documenter tout ajout d'asset ou dépendance.

Licence
- Par défaut : MIT (adapter selon besoin).

Contact
- Pour modifications ou aide : ouvrir une issue ou envoyer un message dans le dépôt.

# Dificulté rencontré 
footer de la @media querry

# Voilà un apperçus de la page
![](./Capture%20d’écran%202025-11-17%20à%2013.16.44.png)
