FROM tomcat:8.5.79-jdk17-temurin-focal
RUN rm -rf /usr/local/tomcat/webapps/*
COPY target/props-v2.war /usr/local/tomcat/webapps/ROOT.war
EXPOSE 8080
CMD ["catalina.sh", "run"]

WORKDIR /usr/local/tomcat
VOLUME /usr/local/tomcat/webapps
