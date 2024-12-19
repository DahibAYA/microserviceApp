# microserviceApp
 1. Microservice Customer-Service
 Gestion des clients (création, lecture, mise à jour, suppression).
- Technologies utilisées : Spring Boot, JPA, H2/MySQL, RESTful API.

 2. Microservice Inventory-Service
-  Gestion des produits (création, lecture, mise à jour, suppression).
- Technologies utilisées : Spring Boot, JPA, H2/MySQL, RESTful API.

 3. Gateway - Spring Cloud Gateway
- : Configuration statique et dynamique des routes pour les microservices.
- Technologies utilisées : Spring Cloud Gateway, YAML.

4. Service Eureka Discovery
- Annuaire pour la découverte des microservices dans l'application.
- Technologies utilisées : Eureka Server (Netflix OSS).

5. Service de Facturation - Billing-Service
- Gestion des factures via OpenFeign pour interagir avec Customer-Service et Inventory-Service.
- Technologies utilisées : Spring Boot, OpenFeign.

 6. Service de Configuration
-  Gestion centralisée des configurations pour les microservices.
- Technologies utilisées : Spring Cloud Config Server.

7. Client Angular
 Interface utilisateur pour interagir avec les microservices (factures, produits, clients).
- Technologies utilisées : Angular, TypeScript, HTML, CSS.
