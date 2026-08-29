# Factoroot

**Factoroot** est un jeu de gestion dans le style de Factorio développé avec le moteur **Godot** pour le hackathon de Aywen.

Votre but est de créer une usine automatisée pour fournir le AywenShop avec des peluches ou des statues de Root en metal. Il faudra donc construire votre usine mais aussi gérer els stocks et vérifier le prix des matières premières

---

## Fonctionnalités principales

* **Construction et Automatisation** : Posez des convoyeurs et des machines pour acheminer et transformer vos ressources en merch pour la boutique de Aiwen
* **Système de Craft Échelonné** : 
  * Transformez des matières premières (Minerai de fer, d'or, charbon, tissu, coton, pétrole).
  * Fabriquez des composants intermédiaires (Lingots, plastique, armatures, membres de peluches).
  * Assemblez les composants en merch (Peluches Root, Root Fer, Root Or).
* **Économie dynamique** : Le prix des matières premières varie en fonction du temps

---

## Fiche Technique

* **Moteur de jeu** : Godot 4 (GDScript)
* **Architecture** : Gestion centralisée des bases de données (`Database`), gestion des grilles et des connexions de convoyeurs (`GridManager`)

---

## Comment jouer (Contrôles)

* **Clic gauche** : Poser le bâtiment sélectionné (nécessite des fonds suffisants).
* **Clic droit** : Supprimer un bâtiment ou un convoyeur.
* **Touche R (`rotate`)** : Pivoter le bâtiment ou le convoyeur avant de le poser.
* ** ZQSD : Bouger la camera
* ** Molette : Zoom avant et arrière

---

## Installation et Lancement

1. Rendez-vous dans les Releases du projet (https://github.com/arthurgugus/Factoroot/releases)
2. Télécharger la dernière version
3. Lancer le jeu
