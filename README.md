# Application de Gestion des Étudiants

## Introduction
Ce projet est une application de gestion qui permet de gérer des étudiants, des filières, des rôles et des utilisateurs. Les étudiants héritent des attributs d'un utilisateur, et il est possible d'affecter des étudiants à des filières et d'attribuer des rôles à des utilisateurs.

L'application a été développée en utilisant les technologies suivantes :

- **Spring Boot** : Un framework Java qui simplifie le développement d'applications web et facilite la création de services RESTful.
- **Postman** : Un outil de test d'API qui permet de tester les endpoints de l'application et de vérifier leur fonctionnement.
- **JPQL** (Java Persistence Query Language) : Un langage de requête pour interagir avec la base de données de manière orientée objet.
- **Swagger** : Un outil de documentation d'API qui génère une documentation interactive pour les endpoints de l'application.

## Technologies Utilisées

### Spring Boot
Spring Boot est un framework Java qui simplifie le développement d'applications en fournissant des solutions prêtes à l'emploi pour les tâches courantes. Il facilite la création de services web RESTful, la gestion de la sécurité, la gestion de la base de données, etc. Dans ce projet, Spring Boot est utilisé pour créer un backend robuste pour notre application.

### Postman
Postman est un outil de test d'API qui permet de tester les endpoints de l'application. Il permet de soumettre des requêtes HTTP aux différentes routes de l'API et de vérifier les réponses. Cela garantit que l'API fonctionne correctement et que les données sont échangées de manière appropriée.

### JPQL (Java Persistence Query Language)
JPQL est un langage de requête pour interagir avec la base de données de manière orientée objet. Il est utilisé pour interroger et manipuler les données stockées dans la base de données de l'application. JPQL permet d'effectuer des opérations de lecture, d'écriture et de mise à jour de données de manière efficace.

### Swagger
Swagger est un outil de documentation d'API qui génère une documentation interactive pour les endpoints de l'application. Il permet aux développeurs et aux utilisateurs de l'API de comprendre comment utiliser l'API, quelles sont les routes disponibles et quels sont les paramètres requis.

## Les taches réalisés

#### La base des données
![BD](https://github.com/Kenza-raki/TP-SpringBoot/assets/116951093/11cb8c4d-5e76-4c8c-b700-0df1a23267ed)

#### Postman
**Post**
![post](https://github.com/Kenza-raki/TP-SpringBoot/assets/116951093/8f626b58-56a3-4e23-83c5-9c1bad65e2e3)

**Put**
![put](https://github.com/Kenza-raki/TP-SpringBoot/assets/116951093/20873ea4-770b-4cc6-8944-940305fa6dd8)

**Get**
![get](https://github.com/Kenza-raki/TP-SpringBoot/assets/116951093/231f0796-83a0-4dfd-b01c-8563da118a42)

**Delete**
![delete](https://github.com/Kenza-raki/TP-SpringBoot/assets/116951093/d06c07ef-3b1c-4959-969f-a3330452c7ea)


#### Swagger

**Post**
![SW-post](https://github.com/Kenza-raki/TP-SpringBoot/assets/116951093/cb57454e-487b-43c1-b58c-9d5755f1b9d7)

**Put**
![SW-put](https://github.com/Kenza-raki/TP-SpringBoot/assets/116951093/4b248ce5-8c05-49a6-9c9b-a6288c7d0279)

**Get**
![SW-get](https://github.com/Kenza-raki/TP-SpringBoot/assets/116951093/ec86c179-1b1d-4c80-b850-e91ff2584ea5)

**Delete**

## Utilisation

### API Endpoints

Vous pouvez utiliser Postman pour tester les endpoints de l'API. Importez la collection de requêtes Postman fournie dans le répertoire `postman`.

### Documentation Swagger

La documentation Swagger de l'API est accessible à l'adresse `http://localhost:8080/swagger-ui.html`. Vous y trouverez une description complète des endpoints et vous pourrez les tester directement depuis l'interface Swagger.

### Exemples d'Endpoints

- Pour créer un nouvel utilisateur : `POST /api/users`
- Pour affecter un rôle à un utilisateur : `POST /api/users/{userId}/roles`
- Pour créer un nouvel étudiant : `POST /api/students`
- Pour affecter une filière à un étudiant : `POST /api/students/{studentId}/filiere`

## Configuration

- La configuration de la base de données se trouve dans `src/main/resources/application.properties`.
- Les entités et les repositories sont définis dans le package `com.votre.package.model` et `com.votre.package.repository`.
- Les contrôleurs pour gérer les requêtes HTTP se trouvent dans `com.votre.package.controller`.
- Les services métier se trouvent dans `com.votre.package.service`.

## Contribuer

Si vous souhaitez contribuer à ce projet, n'hésitez pas à soumettre des demandes d'extraction (pull requests) et des problèmes (issues) sur GitHub.






