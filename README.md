Éclat Pudique — Boutique en ligne
Bienvenue sur Éclat Pudique, une boutique en ligne dédiée aux vêtements et accessoires de mode musulmane. Le site permet aux visiteurs de découvrir les produits, de consulter les prix, d'ajouter des articles à leur panier et de préparer une commande via WhatsApp.
Présentation du projet
Ce projet est un site e-commerce réalisé avec les technologies web de base. Il met en avant une collection de voiles et d'accessoires, dans une interface organisée autour de plusieurs sections : accueil, catégories, promotions, boutique et contact.
Fonctionnalités
- Navigation entre les différentes sections du site.
- Menu adapté aux écrans mobiles.
- Présentation des catégories de produits.
- Catalogue avec images, noms et prix en FCFA.
- Ajout des articles au panier.
- Affichage du nombre d'articles dans le panier.
- Calcul du total du panier.
- Accès à WhatsApp pour préparer une commande.
- Liens vers les réseaux sociaux de la boutique.
Remarque : le passage de commande s'effectue via WhatsApp. Le site ne comporte pas, dans le code fourni, de système de paiement en ligne ou de gestion de commandes côté serveur.

Technologies utilisées
- HTML5 : structure des pages.
- CSS3 : mise en forme et présentation visuelle.
- JavaScript : interactions du menu et du panier.
- WhatsApp : contact et prise de commande.
Structure du projet
Les fichiers et images doivent rester accessibles aux chemins indiqués dans le code HTML. Une organisation possible est :
eclat-pudique/
├── index.html
├── e-commerce2.0.css
├── e-commerce2.0.js
├── Éclat Pudique, élégance dorée.png
├── logoawaN.jpeg
├── panier.jpeg
├── whatsapp1.jpeg
├── whatsapp logo 2.jpeg
├── tiktok logo.jpeg
├── mouslime.jpeg
├── voileleopard.jpeg
├── voileAsma.jpeg
├── voile2en1.jpeg
├── voileKepi.jpeg
├── voile2.jpeg
├── pashmina-couleurU.jpeg
├── pashminaIMpoter.jpeg
├── MINIVOILE.jpeg
├── jerserLOCAL.jpeg
├── manches.jpeg
├── voilechapeau.jpeg
├── jersey.jpeg
├── voilemultiC.jpeg
└── epingleF.jpeg
Les noms de fichiers ci-dessus reprennent ceux référencés dans le HTML fourni. Si ton fichier HTML porte un autre nom, conserve son nom actuel ou adapte cette structure.
Installation et lancement
Aucune installation de dépendances n'est nécessaire pour la version HTML/CSS/JavaScript.
1. Télécharge ou copie les fichiers du projet dans un même dossier.
2. Vérifie que les images portent les mêmes noms que ceux indiqués dans le HTML.
3. Ouvre le fichier HTML principal dans un navigateur (Chrome, Firefox, Edge, etc.).
4. Pour travailler plus facilement dans Visual Studio Code, tu peux utiliser l'extension Live Server, puis cliquer sur Go Live.
Configuration de WhatsApp
Le site utilise actuellement le numéro WhatsApp de la boutique dans ses liens :
- +225 07 14 00 52 85
Pour le modifier, remplace le numéro dans les liens https://wa.me/... du fichier HTML. Dans l'adresse WhatsApp, utilise le numéro au format international, sans espaces ni signe + (par exemple : 2250714005285).

Vérifie également le texte prérempli du lien et le fonctionnement du bouton Commander dans le fichier e-commerce2.0.js.
Modifier les produits
Pour ajouter ou modifier un produit :
1. Ouvre le fichier HTML principal.
2. Repère les blocs <article class="product-cart">.
3. Modifie le nom, l'image, la description et le prix.
4. Vérifie que l'attribut data-product du bouton Ajouter au panier correspond au nom attendu par le JavaScript.
5. Place la nouvelle image dans le dossier prévu et vérifie son chemin.
Les prix affichés sont en francs CFA (FCFA). Pense à les actualiser lorsque les tarifs de la boutique changent.
Personnalisation du design
Le fichier e-commerce2.0.css contient les règles de style. Le fichier e-commerce2.0.js contient la logique interactive du site, notamment celle du panier et de la commande.
Déploiement
Le site peut être publié sur un hébergeur de sites statiques, par exemple Netlify ou GitHub Pages. Avant la publication :
- teste les liens de navigation ;
- vérifie l'affichage sur téléphone, tablette et ordinateur ;
- teste l'ajout et le retrait des articles si cette fonction est prévue dans le JavaScript ;
- vérifie le total du panier et le lien WhatsApp ;
- confirme que toutes les images et les deux fichiers CSS/JavaScript sont bien publiés.
Limites actuelles
D'après le HTML fourni, le site ne présente pas de connexion utilisateur, de base de données, de tableau de bord administrateur ni de paiement en ligne. Les produits et leurs prix sont définis directement dans le code. Ces fonctions nécessiteraient des développements complémentaires.
Contact
- WhatsApp : +225 07 14 00 52 85
- TikTok : @awasoum176
- Site du concepteur : Maewen's
© 2026 — Ma boutique. Tous droits réservés.
