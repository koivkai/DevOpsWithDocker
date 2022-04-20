FROM openjdk:8

WORKDIR /mydir

COPY . .

RUN apt-get update && apt-get install dos2unix

EXPOSE 8080

RUN dos2unix mvnw

RUN ./mvnw package

CMD java -jar ./target/docker-example-1.1.3.jar

