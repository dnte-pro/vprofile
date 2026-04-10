# Prerequisites
#
- JDK 17 or 21
- Maven 3.9
- MySQL 8

# Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- Tomcat
- MySQL
- Memcached
- Rabbitmq
- ElasticSearch
# Database
Here,we used Mysql DB 
sql dump file:
- /src/main/resources/db_backup.sql
- db_backup.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < db_backup.sql



**Multi-service architecture**
You are managing a real stack: Java app, MySQL, Memcached, RabbitMQ, Elasticsearch, and Nginx. That mirrors production-style dependency orchestration.

**Infrastructure automation already included**
The repository contains both Vagrant and Ansible setups, so you can practice Infrastructure as Code, repeatable provisioning, and environment bootstrapping.

**Good CI/CD target**
It is a Maven WAR application, which is perfect for pipeline stages like build, test, package, artifact publishing, and deployment to Tomcat.

**Environment parity practice**
You can compare manual and automated provisioning paths, which is great for learning why drift happens and how automation prevents it.

**Configuration and secrets handling opportunities**
The app relies on service endpoints and credentials, so it naturally teaches config management, variable injection, and secure secret workflows.

**Observability and operations learning**
With multiple components, you get realistic troubleshooting: service health checks, dependency failures, startup order, logs, and network connectivity issues.

**Strong platform for SRE-style skills**
You can practice rollback, idempotent scripts, reproducible environments, and incident debugging in a controlled local lab before production.
