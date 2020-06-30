Product Service
----------------

This is a spring boot microservice which has several product related CRUD REST APIs.

  * This microservice registers and is discoverable via Discover-Service (Eureka Server). 
  * It uses strucutered Controller-Service-Dao/Repo architecture, designed for interfaces.
  * It uses MongoDb as persistence layer and Spring JPA as ORM.
  * AOP is used for logging across applicationn 
