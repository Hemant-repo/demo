FROM tomcat:9.0-alpine
LABEL maintainer="Hemnath"
ADD target/spring-mvc-exmaple.war /usr/local/tomcat/webapps/
EXPOSE 8080
CMD ["catalina.sh", "run"]