# spring-boot-oauth2-uaa
## This project demonstrates the Authorization code grant flow with Spring Security 5.1 and the Pivotal UAA Server
### How to run it  : 

Build the project : ./gradlew clean build

Run the UAA server : ./gradlew -b uaa/build.gradle cargoRunLocal

Run the application : ./gradlew bootRun

Go to http://localhost:8080 and login to your local  UAA server using the springsec5 / password. This is the currently configured user credentials in the scim section of the uaa.yml file .
