# web-service-spring-boot

If you are using Gradle, you can run the application using ./gradlew bootRun.
Or you can build the JAR file using ./gradlew build. Then you can run the JAR file:


java -jar build/libs/gs-rest-service-0.1.0.jar

If you are using Maven, you can run the application using ./mvnw spring-boot:run.
Or you can build the JAR file with ./mvnw clean package. Then you can run the JAR file:

java -jar target/gs-rest-service-0.1.0.jar

If you set the proxy, you can run application by using below command

./mvnw -DproxySet=true -DproxyHost=<host-name> -DproxyPort=80 spring-boot:run