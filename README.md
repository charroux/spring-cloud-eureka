# spring-cloud-eureka

Download and uncompress the project.

Start the registry: 

- open a command line windows  in the eureka-server directory.
- build the project with: ./gradlew build sous Linux ou gradlew build sous Windows.
- launch the registry: java -jar build/libs/eureka-server-0.0.1-SNAPSHOT.jar
- check the registry into a web browser: http://localhost:8761/
- inspect the service : ./gradlew elipse sous Linux ou gradlew eclipse sous Windows.
- import the project under Eclipse: File -> Import -> General -> Existing project into workspace...
- The registry configuration is into https://github.com/charroux/spring-cloud-eureka/blob/master/eureka-server/src/main/resources/application.yml

Start the fisrt service: 

- open a command line windows in the customer-service directory.
- build the project with: ./gradlew build sous Linux ou gradlew build sous Windows.
- launch the registry: java -jar build/libs/customer-service-0.0.1-SNAPSHOT.jar
- check the registry
- inspect the service : ./gradlew elipse sous Linux ou gradlew eclipse sous Windows.
- import the project under Eclipse: File -> Import -> General -> Existing project into workspace...
- The registry configuration is into https://github.com/charroux/spring-cloud-eureka/blob/master/customer-service/src/main/resources/application.yml

Start the second service: 

- open a command line windows in the customer-client-service directory.
- build the project with: ./gradlew build sous Linux ou gradlew build sous Windows.
- launch the registry: java -jar build/libs/customer-client-service-0.0.1-SNAPSHOT.jar
- check the registry
- inspect the service : ./gradlew elipse sous Linux ou gradlew eclipse sous Windows.
- import the project under Eclipse: File -> Import -> General -> Existing project into workspace...
- The registry configuration is into https://github.com/charroux/spring-cloud-eureka/blob/master/customer-client-service/src/main/resources/application.yml
- Test the hole project: http://localhost:9099/customer-client/1

