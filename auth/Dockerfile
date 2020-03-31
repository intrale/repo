FROM openjdk:12
VOLUME /tmp
EXPOSE 8888
ADD ./target/auth-0.0.1-SNAPSHOT.jar auth.jar
ENTRYPOINT ["java", "-jar", "/auth.jar"]