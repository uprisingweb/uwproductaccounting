# Configuration du module de Comptabilité des produits pour Dolibarr v11.x

## Description

Modification de la page de gestion des comptes comptables des produits.
Ajoute :
- Un tri par catégorie / tag
- Possibilité d'attribuer un même compte comptable à l'ensemble des produits sélectionnés

## Installation

1 - Télécharger ce depot : bouton vert "Clone or download" en haut à droite de cette page, sélection "Download ZIP"
2 - Dans Dolibarr :
	- aller dans "Accueil" > "Configuration" > "Modules/Applications"
	- aller sur l'onglet "Déployer/Installer un module externe"
	- Changer le ZIP que vous venez des télécharger
	- Ensuite, dans l'onglet "Modules/applications installés" tout en bas activez le module "Comptabilité des produits - Gestion comptable des produits par catégorie"

> A noter que ce module necessite l'activation du module "Comptabilité avancée" et du module "Libellés/Catégories"

3 - Pas besoin d'aller le configurer
	- Un lien "Comptes produits v2" est maintenant disponible dans dans le menu "Comptabilité" > "Configuration" 

## Comment l'utiliser ?

1- Filtres / Options
- Sélectionner de “Mode Ventes” pour definir les comptes comptables de ventes
- Sélectionner de “Mode Achats” pour definir les comptes comptables d’achats
- Tags/catégorie : permet de restreindre la sélection des produits par catégorie

> bouton “Rafraichir” pour appliquer les filtres

2- Listes des produits/services
- Pagination : Changer le 25 de la liste déroulante en 5000 pour afficher tous résultats sur une seule page
- “Nouveau compte à assigner à l'ensemble des produits sélectionnés ci-dessous” : Permet de définir le compte comptable à assigner à l’ensemble des produits qui seront sélectionnés, on peut sinon définir le compte sur chaque ligne, il faut alors laisser ce 1er champ vide et sélectionner un compte dans “Nouveau compte à assigner” sur chaque ligne
- Si besoin dans l’en-tête du tableau changer le champs “Sans compte dédié valide” en “Avec compte dédié valide” et cliquez sur la “loupe” pour valider ce filtre
- Cliquer sur la case à cocher en haut à droit pour sélectionner l’ensemble des produits, ou ne sélectionner que les produits à modifier

> bouton “enregistrer” au dessus du tableau pour valider l’ensemble des produits sélectionnés (le bouton reste grisé tant qu’aucun produit est sélectionné)


## Développeur

Développé par Uprising-web 

https://www.uprising-web.com


## Licenses

GPLv3

