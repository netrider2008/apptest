apptest
=======

test repo

1. Spring Boot Admin Server
mvn clean install
mvn spring-boot:run
starts on port 8080
login with admin/admin
to activate mail notifications uncomment the starter mail dependency and the mail configuration from application.properties
add some real credentials if you want the app to send emails
to activate Hipchat notifications proceed same as for email
2. Spring Boot App Client
mvn clean install
mvn spring-boot:run
starts on port 8081
basic auth client/client
Relevant Articles:
A Guide to Spring Boot Admin
https://www.javainuse.com/spring/spring_cloud_config_server
https://codecentric.github.io/spring-boot-admin/current/
https://codecentric.github.io/spring-boot-admin/1.3.4/
https://www.baeldung.com/spring-boot-admin
