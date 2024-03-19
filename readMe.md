# OBJECTIF
Utilisation de flex, de bootstrap et du responsive

## Méthode de travail

- Observer :
    - Bien analyser toute les subtilités des 3 maquettes
    - Quels sont les éléments qui sont affichés différemment ?

- Ecrire le HTML en premier :
    - Toujours commencer par le HTML car on va d'abord écrire le contenu et ensuite poser le design
    - Utiliser les balises sémantiques en priorité, et ensuite les balises génériques

- Écrire le CSS :
    - Utiliser préférentiellement SASS (BONUS sur la note finale)
    - Construire votre page dans l'ordre de lecture de la page HTML
    - Commencer par la version desktop, puis tablette et Mobile en dernier

# INSTRUCTIONS
Utiliser le mockup pdf pour réaliser la page html
Créer et coder le fichier index.html
Créer et coder le fichier css/style.css (en utilisant sass pour avoir un bonus)

## 1. RENDU DEMANDÉ

### 1.1. Mobile

![Maquette mobile](docs/mobile.jpg)

### 1.2. Tablette

![Maquette Tablette](docs/tablette.jpg)

### 1.3. Desktop

![Maquette Desktop](docs/desktop.jpg)

### 1.4. Modal

![Apercu de la fenêtre modale](docs/modal.jpg)

## 2. BOOTSTRAP
- Rendre les boutons `Lire la suite...` cliquables en inserant un modal boostrap unique pour tous les boutons 
- Le modal sera mis en forme (voir 1.4. modal) et comprendra :
  - Un titre
  - Un text en lorem
  - et la video youtube se trouvant à cette adresse : https://www.youtube.com/watch?v=RJ1MD-t1Pag

## 3. CSS
- Utiliser un fichier normalize css ou reboot css
- Réalisation de l'exercice en desktop-first
- Utilisation des media queries
- Utilisation des propriétés flex
- Les `breackpoints` :
    - Mobile : 450px
    - Desktop : 780px
- Les polices seront les google fonts suivantes :
  - `Noto Sans JP` pour les headings
  - `Quicksand` pour le reste
- Les couleurs seront à retrouver via les images fournies

## 4. En plus :
- Ajouter une puce avec `fontawesome` pour le lire la suite et faire disparaitre cette puce pour les écrans mobiles
- Réaliser des effets hover avec des transitions douces lorsque l'on survole :
  - les boutons : changement de couleur du fond et du texte
  - les sections : qui deviennent moins opaque au survol en mode desktop (voir desktop.jpg)
- Utilisation de `sass` pour coder le css
