FROM bitnami/java:11-prod
LABEL Owner="Ryan Clair"

ADD target/fortune-0.0.1-SNAPSHOT.jar app.jar

ENTRYPOINT ["java", "-Djava.security.egd=file:/dev/./urandom","-Xmx512m", "-jar", "/app.jar"]