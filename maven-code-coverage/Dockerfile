FROM java:8
WORKDIR /
ADD target/maven-code-coverage.jar app.jar
EXPOSE 8080
CMD java - jar app.jar
