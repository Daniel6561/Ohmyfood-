# Oh my food !
Troisième projet du parcours "Développeur web" chez OpenClassroom.
L'objectif est d'intégrer la maquette d'un site de foodtech nommé "Ohmyfood" permettant la commande de repas en ligne (voir l'image en suivant les liens ci-dessous).

![maquette accueil ohmyfood](./assets/maquettes/accueil.png)
et la page du menu d'un restaurant
![maquette menu ohmyfood](./assets/maquettes/Menu - La palette du goût.png)


## Technologies
- Le développement devra se faire en CSS, sans JavaScript
- Aucun framework ne devra être utilisé, en revanche l’utilisation de SASS serait un plus
- Aucun code CSS ne devra être appliqué via un attribut style dans une balise HTML.


## Compatibilité
La cible étant les personnes connectées et pressées, le site sera développé en utilisant l’approche mobile-first. Pour cette raison, seules des maquettes mobiles seront réalisées. Sur tablette et desktop, le site devra s’adapter, mais ces supports n’étant pas prioritaires, leur mise en page est libre
- L’ensemble du site devra être responsive sur mobile, tablette et desktop.
- Les pages devront passer la validation W3C en HTML et CSS sans erreur.
- Lien vers la validité CSS [ http://jigsaw.w3.org/css-validator/validator$link ]
- Le site doit être parfaitement compatible avec les dernières versions desktop de Chrome et Firefox.


## Contenu des pages

### Page d'accueil
- Affichage de la localisation des restaurants. À terme il sera possible de choisir sa localisation pour trouver des restaurants proches d’un certain lieu.
- Une courte présentation de l’entreprise.
- Une section contenant les 4 menus sous forme cartes. Au clic sur la carte, l’utilisateur est redirigé vers la page du menu.

### Pages de menu
- 4 pages contenant chacune le menu d’un restaurant.

### Header
- Le header est présent sur toutes les pages.
- Sur la page d’accueil, il contient le logo du site.
- Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil

### Footer
- Le footer est identique sur toutes les pages.
- Au clic sur “Contact”, un renvoi vers une adresse mail est effectué.


## Effets graphiques
### Boutons
- Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir. L’ombre portée devra également être plus visible.
- À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un bouton "J’aime" en forme de cœur est présent sur la maquette. Au clic, il devra se remplir progressivement. Pour cette première version, l’effet peut être apparaître au survol sur desktop au lieu du clic

### Page d’accueil
- Quand l’application aura plus de menus, un “loading spinner” sera nécessaire. Sur cette maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 1 à 3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini, toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte graphique du site.

### Pages de menu
- À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe “Entrée”, “Plat” et “Dessert”. Un exemple de l’effet attendu est fourni.
- Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus. Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol sur desktop au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec des points de suspension. Un exemple de l’effet attendu est fourni.

## Identité graphique
### Polices
- Logo et titres: Shrikhand
- Texte: Roboto
- Les icones proviennent de [Font Awesome](https://fontawesome.com/)
- Les couleurs sont : primaire #9356DC - secondaire #FF79DA - tertiaire #99E2D0


## Notes sur la réalisation du projet
- Le fichier de style se trouve à l'adresse (./style/style.css)
- Le fichier html ou page web se trouve à l'adresse (./index.html)
- Le dossier de police se trouve à l'adresse (./style/Police/)
- Le dossier des icônes se trouve à l'adresse (./icons/)
