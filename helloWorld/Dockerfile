FROM openjdk:7
COPY . helloWorld
WORKDIR helloWorld
RUN javac -d ./helloWorld HelloWorld.java
ENTRYPOINT ["java", "HelloWorld"]
