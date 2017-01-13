FROM  tomcat:jre8-alpine

COPY /storagefiles /mnt/data/basicstorage

COPY /gatekeeper.war /usr/local/tomcat/webapps/gatekeeper.war
COPY /gatekeeper.xml /usr/local/tomcat/conf/Catalina/localhost/gatekeeper.xml
COPY /systemone.jar /usr/local/tomcat/lib/systemone.jar
#build with maven build


#build with:
#maven build

#start on build server with:
#docker run --network=cora-test --name gatekeeper-test -d  gatekeeper

#start on external with:
#docker run --network=cora --name gatekeeper -d  gatekeeper
