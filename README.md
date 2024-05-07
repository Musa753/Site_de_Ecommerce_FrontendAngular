Aperçu

Ce projet est une application web destinée à la gestion de la recherche de produits, de l'inscription des utilisateurs, de la connexion, des fonctionnalités du panier d'achat, du placement de commandes et de la confirmation des commandes. L'application est structurée autour de plusieurs modules et composants, chacun étant responsable de fonctionnalités spécifiques.


Aperçu Visuel

Pour avoir un aperçu visuel de l'application, veuillez consulter les images fournies dans le dossier "aperçu" de ce dépôt. Ces images montrent différentes parties de l'interface utilisateur, y compris les pages d'accueil, de recherche, de connexion, de gestion du panier et de confirmation de commande.

Modules et Composants

    Module de Recherche
        Composant SearchByName : Gère la recherche de produits par nom.
        Composant SearchByPrice : Gère la recherche de produits par prix.
        Composant SearchResult : Affiche les résultats de la recherche.

    Module Principal
        Composant SignIn : Gère l'inscription des utilisateurs.
        Composant LogIn : Gère la fonctionnalité de connexion des utilisateurs.
        Composant SingleProduct : Affiche les détails individuels d'un produit.
        Composant ProductSheet : Affiche des informations détaillées sur un produit.
        Composant ProductList : Affiche une liste de produits.
        Composant NavBar : Barre de navigation incorporant la fonctionnalité de recherche.
        Composant Order : Gère le placement des commandes.
        Composant OrderResult : Affiche un message de confirmation de commande.

    Module Panier
        Composant Basket : Gère les produits ajoutés au panier d'achat.

Détails des Composants

    Composant SearchByName : Permet aux utilisateurs de rechercher des produits par nom. Il comprend une barre de recherche et gère l'interaction avec le service de recherche pour afficher les résultats.

    Composant SearchByPrice : Permet aux utilisateurs de rechercher des produits par prix. Similaire à SearchByName, il interagit avec le service de recherche pour afficher les résultats.

    Composant SearchResult : Affiche les résultats des recherches de produits. Il utilise le Composant SingleProduct pour présenter chaque produit dans les résultats de recherche.

    Composant SignIn : Gère l'inscription des utilisateurs en capturant les informations utilisateur via un formulaire réactif. Il interagit avec les variables globales pour stocker les données utilisateur.

    Composant LogIn : Gère la fonctionnalité de connexion des utilisateurs, en les redirigeant en fonction de leurs informations d'identification ou en les incitant à s'inscrire s'ils ne sont pas déjà enregistrés.

    Composant SingleProduct : Affiche les détails individuels d'un produit, offrant des options pour ajouter le produit au panier d'achat ou afficher sa description détaillée.

    Composant ProductSheet : Similaire à SingleProduct, il affiche des informations détaillées sur un produit et offre la possibilité de l'ajouter au panier d'achat.

    Composant ProductList : Affiche une liste de produits en utilisant le modèle du composant SingleProduct.

    Composant NavBar : Représente une barre de menu avec fonctionnalité de recherche, utilisant des modèles de SearchByName et SearchByPrice.

    Composant Order : Gère la saisie des informations de livraison et la validation de la commande, avec des options pour passer à la confirmation de commande ou revenir à la page d'accueil.

    Composant OrderResult : Affiche un message de confirmation lors du placement réussi d'une commande.

    Composant Basket : Gère la gestion des produits ajoutés au panier d'achat, y compris les fonctionnalités d'ajout, de suppression et de mise à jour des quantités de produits.

Utilisation

    Cloner le dépôt sur votre machine locale.
    Installer les dépendances avec npm install.
    Exécuter l'application avec ng serve. 
