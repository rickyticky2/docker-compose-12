FROM tomcat
WORKDIR /usr/local/tomcat/
RUN mkdir /usr/local/tomcat/webapps/ROOT
EXPOSE 8080
RUN cd /usr/local/tomcat/webapps && ls -la
CMD ["catalina.sh", "run"]
