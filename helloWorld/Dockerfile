FROM openjdk:7
COPY . helloWorld
WORKDIR helloWorld
RUN javac HelloWorld.java -d ./helloWorld
ENTRYPOINT ["java", "HelloWorld"]
