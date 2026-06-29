#https://www.youtube.com/watch?v=FNM6JwycIXI
Spring Cloud Config Explained | Centralized Config for Microservices (with Git + Refresh Demo)


Postman

http://localhost:8889/config
o/p App Name from Config Server: Dev Application With Refresh Scope


After update in congi-repo (application-dev.yaml )..appname is application and dev is active profile from config
run below url to refresh without restart server
http://localhost:8889/actuator/refresh


impact app congi-repo congi-client  congi-server

https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_quick_start
