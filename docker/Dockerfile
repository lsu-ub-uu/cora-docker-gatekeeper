FROM  tomcat:9.0-jre11-slim

#COPY /storagefiles /mnt/data/basicstorage

COPY /gatekeeperserver.war /usr/local/tomcat/webapps/gatekeeperserver.war
COPY /gatekeeperserver.xml /usr/local/tomcat/conf/Catalina/localhost/gatekeeperserver.xml
COPY /userpicker.jar /usr/local/tomcat/lib/userpicker.jar
COPY /basicstorage.jar /usr/local/tomcat/lib/basicstorage.jar


#build with:
#maven build

#start on development with:
#docker run --net=cora -v /mnt/data/basicstorage -p 8081:8080  --name gatekeeper -d  gatekeeper 

#start on build server with:
#docker run --net=cora-test -v /mnt/data/basicstorage --name gatekeeper-test -d  gatekeeper

#start on external with:
#docker run --network=cora --name gatekeeper -d  gatekeeper
