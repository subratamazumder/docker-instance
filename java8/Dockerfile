################################################################
##
## PURPOSE:
## customized java server for spring boot application
##
## HISTORY:
## 23:08 24-March-2016 created 
##
## PREREQUSITES:
## 1. <none>
##
################################################################
FROM java

MAINTAINER "Subrata <subrata.besu@gmail.com>"

RUN mkdir -p /usr/local/java/spring-boot-jar

ADD ./gs-spring-boot-0.1.0.jar /usr/local/java/spring-boot-jar

RUN java -jar /usr/local/java/spring-boot-jar/gs-spring-boot-0.1.0.jar

#more command
