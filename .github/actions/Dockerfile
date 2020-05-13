FROM openjdk:8u131-jre-alpine
ENV testShit=/opt/hello-world
ADD HelloWorld.class $testShit/
WORKDIR $testShit
ENTRYPOINT ["java", "HelloWorld"]
