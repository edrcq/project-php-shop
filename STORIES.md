# Projet PHP-BDD

1.
En tant que visiteur
je souhaite voir les produits du site
afin de 3.

Contraintes:
- L'utilisateur doit pouvoir chercher un produit avec un champs de recherche (comme sur amazon)
- Les produits ont une page dédiée (exemple /?p=product&slug=lampe-de-chevet)
- Les produits peuvent être filtré par catégorie (/?p=category&slug=lampes)

2.
En tant qu'admin je souhaite voir une liste des produits

Contraintes:
- Sur chaque produit un bouton/lien est disponible afin de le modifier et supprimer.
- Chaque produit possède une quantité en stock
- Bonus: Prix promotionnel

2A.
En tant qu'admin
je souhaite pouvoir ajouter un produit
afin de 1.

Contraintes:
- Un formulaire pour ajouter un produit
- Vous ne devez pas gérer l'upload d'image (c'est bonus)

2B.
En tant qu'admin
je souhaite pouvoir modifier un produit
afin de 1.

Contraintes:
- Un formulaire pour modifier un produit
- Vous ne devez pas gérer l'upload d'image (c'est bonus)
- La page ne doit être accessible uniquement par un admin (role stocké en BDD)
- ( /?p=admin_change_product&id=2 )

2C.
En tant qu'admin
je souhaite pouvoir modifier un produit
afin de 1.

Contraintes:
- Un formulaire pour modifier un produit
- Vous ne devez pas gérer l'upload d'image (c'est bonus)
- La page ne doit être accessible uniquement par un admin (role stocké en BDD)
- ( /?p=admin_change_product&id=2 )

3.
En tant qu'utilisateur
je souhaite pouvoir ajouter un produit à mon panier
afin de passer une commande (5)

Contraintes:
- Il faut une page panier
- Cette page contient un bouton: Passer la commande
- Bonus: Gérer le panier en JS

4.
En tant qu'utilisateur
Je souhaite passer une commande

Contraintes:
- Une page est dédiée à cet effet avec un formulaire dans lequel l'utilisateur entre son adresse de livraison.
- Une commande ne doit pas pouvoir etre passée si un article n'est plus en stock
- Lorsqu'une commande est passée, mettre à jour le stock disponible

5.
En tant qu'admin
Je souhaite voir les commandes passées
afin de changer leur statut

Contraintes:
- Filtrer les commandes par statut (Nouvelle, Envoyée, Finie, Retour Client, Toutes)
- Un bouton doit être présent afin de changer le statut de la commande.
- Triée par date de création (de la plus récente à la plus vieille)
- Pouvoir changer le tri par Date de mise à jour
- Lorsque vous changer le statut d'une commande, la date de mise à jour..ce met à jour

6.
En tant qu'utilisateur
je souhaite pouvoir ajouter un commentaire et un nombre d'etoile sur un produit

Contraintes:
- On doit avoir commander au moins une fois le produit pour pouvoir le commenter.

7.
Le client doit avoir accès a la liste de ses commandes et doit voir les détails de celle-ci.


8. 
En tant qu'utilisateur je souhaite m'inscire et me connecter sur le site

Contraintes:
- Mot de passe hashé
- Role utilisateur et administrateur
