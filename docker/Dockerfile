ARG CORA_DOCKER_VERSION
FROM cora-docker-tomcat:${CORA_DOCKER_VERSION}

COPY /systemone-gatekeeper-war*.war /usr/local/tomcat/webapps/gatekeeperserver.war
COPY /gatekeeperserver.xml /usr/local/tomcat/conf/Catalina/localhost/gatekeeperserver.xml