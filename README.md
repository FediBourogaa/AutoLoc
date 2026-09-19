# AutoLoc - Plateforme de gestion de location de véhicules multi-agences

## Atelier 0 : Mise en place de l'environnement

### Objectifs du projet
Développement d'une chaîne d'outils Java / Spring Boot complète pour la plateforme de gestion AutoLoc.

### Liste des acteurs et cas d'utilisation identifiés (Séance 1)
Conformément aux spécifications du projet, voici les quatre acteurs principaux qui interagiront avec l'application :

* **Client** : Consulter les services de location, rechercher des véhicules disponibles, et effectuer des réservations en ligne.
* **Agent d'agence** : Gérer les contrats de location, effectuer les états des lieux (départ/retour), et accueillir les clients.
* **Responsable d'agence (Manager)** : Superviser la flotte de véhicules de son agence, suivre le chiffre d'affaires local, et gérer le planning de son équipe.
* **Administrateur** : Configurer la plateforme globale, gérer les comptes des utilisateurs (agents/responsables), et administrer le référentiel des agences.

## Configuration Technique
* **Back-end** : Java 17 (Oracle OpenJDK) & Spring Boot 3.x
* **Base de données** : MySQL 8.x via XAMPP (`autoloc_db`)
