FROM openjdk:8-jre
WORKDIR /app
COPY target/shopfront-0.0.1-SNAPSHOT.jar	 /app/myapp.jar
//COPY target/myapp.jar /app/myapp.jar

EXPOSE 8010
ENTRYPOINT ["java","-jar","/app/myapp.jar"]
