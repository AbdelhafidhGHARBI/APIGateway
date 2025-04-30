# APIGateway
Passerelle API (API Gateway) basée sur Spring Cloud Gateway avec routage statique vers les microservices MSCompte et MSBanque. Elle assure la centralisation des points d'entrée, le filtrage des requêtes HTTP, et la gestion des chemins d'accès pour une architecture distribuée RESTful.

Fonctionnalités :

Routage statique via application.yml
Communication entre services via Eureka (si activé plus tard)
Préparation pour intégrer des filtres globaux (log, auth, CORS…)
