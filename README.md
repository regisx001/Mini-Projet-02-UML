# Projet de Supervision de Production pour Composants Automobiles

## Description du Projet

Ce projet vise à développer un système de supervision de production pour des composants automobiles. Le système permet de :

- Assurer la traçabilité complète de la production.
- Superviser en temps réel les performances des équipements.
- Gérer la qualité et la maintenance des équipements.
- Fournir des analyses et des rapports détaillés pour améliorer la gestion de la production.

## Outil de Modélisation Utilisé

Pour la modélisation des diagrammes, **PlantUML** a été utilisé. Ce choix a été motivé par :

- **Compatibilité avec Linux** : PlantUML fonctionne nativement sur Linux et permet une intégration facile dans des processus automatisés de génération de diagrammes.
- **Simplicité et flexibilité** : Les diagrammes sont générés à partir de fichiers texte, facilitant leur mise à jour et gestion au cours du projet.
- **Collaboration via GitHub** : Les fichiers source des diagrammes sont stockés sur **GitHub**, permettant une gestion centralisée et une collaboration efficace.

## Structure du Projet

Ce projet inclut les diagrammes suivants :

## Diagrammes Statiques
- ### Diagramme de Cas d'Utilisation : Représente les interactions entre le système et les acteurs.
- ![Diagramme_Cas_Utilisation](https://github.com/user-attachments/assets/1bba13ce-9e72-49c9-b1ca-3384a1bff85e)

- ### Diagramme de Classes : Montre la structure statique du système, avec ses classes, attributs et relations.
- ![Diagramme_Classes](https://github.com/user-attachments/assets/520a23b7-6e09-4ff4-a4c1-c9af99a82ac2)


## Diagrammes Dynamiques
- ### Diagramme de Séquence : Représente les interactions entre les objets dans le temps.
- #### Démarrage d'un ordre de fabrication :
- ![Diagramme_séquence_Démarrage_ordre_fabrication](https://github.com/user-attachments/assets/a94b7e11-2d17-4f12-aa9a-4416ba71388e)
- #### Gestion d'une non-conformité :
- ![Diagramme_Séquence_Gestion_non-conformité](https://github.com/user-attachments/assets/9084c53f-f686-420a-b0dc-0946a44835ab)


- ### Diagramme d'Activité : Décrit les processus dynamiques du système.
- #### Processus de production:
- ![Diagramme_activité_Processus_Production](https://github.com/user-attachments/assets/704b9e1d-3203-4f73-ad61-98ad728f3684)
- #### Processus de qualité:
- ![Diagramme_activité_Processus_Qualité](https://github.com/user-attachments/assets/4ad90665-159e-41a8-b025-42e06a58131e)


- ### Diagramme d'État-Transition : Montre les états d'un objet et les transitions entre ces états.
-  #### États d'un ordre de fabrication :
-  ![Diagramme_État-Transition_Ordre_Fabrication](https://github.com/user-attachments/assets/1e67b258-333e-439d-b508-897537e967b0)
-  #### États d'un équipement:
-  ![Diagramme_État-Transition_États_Équipement](https://github.com/user-attachments/assets/95b4f4bc-56dd-4e68-9ada-20b7d0cd5a83)




## Installation et Génération des Diagrammes

1. **Clonez le dépôt GitHub** :
   ```bash
   git clone https://github.com/username/projet-diagrammes.git
