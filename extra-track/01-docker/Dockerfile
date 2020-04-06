FROM adoptopenjdk/openjdk11:x86_64-debianslim-jdk-11.0.6_10-slim

ADD target/dropwizard-example-1.0-SNAPSHOT.jar /data/dropwizard-example-1.0-SNAPSHOT.jar
ADD ../dropwizard-example/example.yml /data/example.yaml

CMD java -jar /data/dropwizard-example-1.0-SNAPSHOT.jar server /data/example.yaml
EXPOSE 8080