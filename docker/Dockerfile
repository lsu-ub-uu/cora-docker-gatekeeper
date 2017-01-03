FROM  tomcat:jre8-alpine

COPY /storagefiles /mnt/data/basicstorage

COPY /gatekeeper.war /usr/local/tomcat/webapps/gatekeeper.war
COPY /gatekeeper.xml /usr/local/tomcat/conf/Catalina/localhost/gatekeeper.xml
COPY /systemone.jar /usr/local/tomcat/lib/systemone.jar
#build with maven build
#start with docker run  --name gatekeeper -d  gatekeeper
