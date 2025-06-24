# Documentation API – Node-etudiant-API

## Sommaire
1. Présentation du projet  
2. Modèle de données (Etudiant)  
3. Routes API disponibles  
4. Exemples de requêtes  
5. Codes HTTP utilisés  
6. Équipe projet  

---

## 1. Présentation du projet

Node-etudiant-API est une API REST développée en Node.js avec le framework Express et l’ORM Sequelize.  
Elle permet la gestion des étudiants (CRUD) stockés dans une base de données MySQL nommée `dbUniversite`.

### Objectifs :
- Permettre de créer, lire, modifier et supprimer des étudiants via des routes REST.
- Utiliser Sequelize pour interagir avec la base de données de manière sécurisée et modulaire.
- Fournir une structure propre avec séparation des responsabilités : modèle, routes, connexion à la base de données.

### Structure du projet :
