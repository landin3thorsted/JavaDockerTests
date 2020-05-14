FROM openjdk:7
COPY . helloWorld
WORKDIR helloWorld
RUN javac HelloWorld.java -cp ./helloWorld
ENTRYPOINT ["java", "HelloWorld"]
