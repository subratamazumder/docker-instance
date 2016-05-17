################################################################
##
## PURPOSE:
## customized tomcat server for maven deployments
##
## HISTORY:
## 23:08 24-March-2016 created 
##
## PREREQUSITES:
## 1. <none>
##
################################################################
FROM tomcat:8-jre8

MAINTAINER "Subrata <subrata.besu@gmail.com>"

RUN mkdir -p /usr/local/tomcat/conf

ADD ./settings.xml /usr/local/tomcat/conf/

ADD ./tomcat-users.xml /usr/local/tomcat/conf/
