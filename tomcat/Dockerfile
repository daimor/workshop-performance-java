FROM tomcat:latest
#FROM ubuntu:latest
#RUN apt-get -y update && apt-get -y upgrade
#RUN apt-get -y install openjdk-8-jdk wget
#RUN mkdir /usr/local/tomcat
#RUN wget https://dlcdn.apache.org/tomcat/tomcat-8/v8.5.89/bin/apache-tomcat-8.5.89.tar.gz -O /tmp/tomcat.tar.gz
#RUN cd /tmp && tar xvfz tomcat.tar.gz
#RUN cp -Rv /tmp/apache-tomcat-8.5.89/* /usr/local/tomcat/
COPY /tomcat/performance.war /usr/local/tomcat/webapps/
#EXPOSE 8080
CMD /usr/local/tomcat/bin/catalina.sh run