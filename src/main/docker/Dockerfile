FROM frolvlad/alpine-oraclejdk8:slim
VOLUME /tmp
ADD matcher-discovery-server-*.jar app.jar
EXPOSE 9090
RUN sh -c 'touch /app.jar'
ENTRYPOINT ["java","-jar","/app.jar"]
