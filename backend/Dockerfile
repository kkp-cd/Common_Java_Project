FROM openjdk:8
WORKDIR /app
#COPY backend/target/backend-1.0-RELEASE.jar /app/backend.jar
#CMD ["java", "-jar", "/app/backend.jar"]

#this can be used when you build the war file by using the backend/pom.xml not the parenet pom.xml
COPY target/backend-1.0-RELEASE.jar /app/backend.jar  
CMD java -jar backend.jar