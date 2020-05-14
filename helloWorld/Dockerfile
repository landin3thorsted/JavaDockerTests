FROM openjdk:7
COPY . helloWorld
WORKDIR helloWorld
RUN javac HelloWorld.java -cp ./helloWorld
CMD ["java", "HelloWorld"]
