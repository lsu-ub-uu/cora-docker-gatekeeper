FROM tomcat:9.0.37-jdk14-openjdk-buster

COPY /systemone-gatekeeper-war*.war /usr/local/tomcat/webapps/gatekeeperserver.war
COPY /gatekeeperserver.xml /usr/local/tomcat/conf/Catalina/localhost/gatekeeperserver.xml

COPY /*.properties /usr/local/tomcat/lib/

#build with:
#maven build

#start on development with:
#docker run --net=cora -v /mnt/data/basicstorage -p 8081:8080  --name gatekeeper -d  gatekeeper 

#start on build server with:
#docker run --net=cora-test -v /mnt/data/basicstorage --name gatekeeper-test -d  gatekeeper

#start on external with:
#docker run --network=cora --name gatekeeper -d  gatekeeper
