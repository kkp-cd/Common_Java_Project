FROM openjdk:8
WORKDIR /app
run mkdir -p src/main/webapp/resources target
COPY src/main/webapp/* /app/src/main/webapp/
COPY target/frontend-1.0-RELEASE.jar /app/target/frontend.jar
CMD java -Dapi.host.baseurl=${BACKEND} -jar target/frontend.jar



#COPY frontend/src/main/webapp/* /app/src/main/webapp/
#COPY frontend/target/frontend-1.0-RELEASE.jar /app/target/frontend.jar
#CMD java -Dapi.host.baseurl=${BACKEND} -jar /app/target/frontend.jar
# Use BACKEND env variable (added by Krishna team)
#ENV BACKEND_URL=http://backend-service:8080

#CMD java -Dapi.host.baseurl=${BACKEND_URL} -jar target/frontend.jar
