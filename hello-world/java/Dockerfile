FROM maven:3.8.3-openjdk-17 

WORKDIR /app

COPY . .

RUN mvn clean install

EXPOSE 9090 

CMD ["java","-jar","/app/target/hello-docker-app-1.0.0.jar"]
