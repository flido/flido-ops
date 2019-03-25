FROM maven
VOLUME /opt/app
ADD web-perf /opt/app
WORKDIR /opt/app/web-perf
CMD mvn package
CMD cp target/*.jar ./app.jar
CMD pwd
CMD ls
#COPY *.jar app.jar
#ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","./app.jar"]
