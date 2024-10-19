# TP - Hibernate 2

## Description du Projet

Ce projet démontre l'utilisation d'Hibernate, un framework de persistance pour Java, dans la gestion d'une base de données MySQL. Le projet se concentre sur l'implémentation d'opérations CRUD (Create, Read, Update, Delete) sur les entités `Salle` et `Machine` via des services, tout en assurant la persistance des données grâce à Hibernate.

## Objectifs

- Intégrer une base de données MySQL avec une application Java à l'aide d'Hibernate.
- Simplifier les opérations CRUD en utilisant des services et des DAO.
- Écrire des tests unitaires pour garantir le bon fonctionnement de l'application.

## Technologies Utilisées

- **Java 8**
- **Hibernate ORM**
- **MySQL**
- **Maven** : Pour la gestion des dépendances.
- **JUnit** : Pour les tests unitaires.

## Structure du Projet

Le projet est structuré comme suit :

- **src/main/java** : Contient les entités, les services, et la configuration Hibernate.
  - `entities` : Définit les entités `Machine` et `Salle`.
  - `services` : Implémente la logique métier pour gérer les entités.
  - `utils` : Fournit la classe `HibernateUtil` pour la gestion des sessions.
- **src/test/java** : Contient les tests unitaires.

## Étapes de Développement

### 1. Configuration de Maven
Le fichier `pom.xml` gère les dépendances comme Hibernate, MySQL Connector et JUnit.

### 2. Configuration de Hibernate
Le fichier `hibernate.cfg.xml` est utilisé pour configurer la connexion à la base de données MySQL, ainsi que les propriétés de Hibernate telles que le dialecte SQL et la mise à jour automatique du schéma.

### 3. Création des Entités
Les entités `Machine` et `Salle` sont mappées aux tables de la base de données. Les annotations JPA sont utilisées pour gérer les relations entre les entités.

### 4. Implémentation des Services
Les services `MachineService` et `SalleService` gèrent les opérations CRUD en utilisant Hibernate.

### 5. Tests Unitaires
Les tests unitaires avec JUnit valident les fonctionnalités CRUD et les requêtes personnalisées comme la recherche des machines entre deux dates.

## Conclusion

Ce projet démontre l'utilisation d'Hibernate pour gérer la persistance des données avec MySQL dans une application Java. L'utilisation de Maven et JUnit a facilité l'intégration des bibliothèques nécessaires et l'écriture des tests pour valider les fonctionnalités du projet.

## Lien vers le Projet GitHub

Vous pouvez accéder au code complet du projet via ce lien : [TP2 Hibernate](https://github.com/Baadr003/TP2Hibernate)
