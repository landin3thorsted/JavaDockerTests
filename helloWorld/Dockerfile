FROM openjdk:7
COPY . helloWorld
WORKDIR helloWorld
RUN javac -d /home/runner/work/JavaDockerTests/JavaDockerTests/./helloWorld HelloWorld.java
ENTRYPOINT ["java", "HelloWorld"]
