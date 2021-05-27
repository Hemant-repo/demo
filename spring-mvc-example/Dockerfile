FROM tomcat:9.0-alpine
LABEL maintainer="Hemnath"
ADD target/spring-mvc-example.war /usr/local/tomcat/webapps/
EXPOSE 9002
CMD ["catalina.sh", "run"]