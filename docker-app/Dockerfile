FROM beijing.artifactory.com:5001/docker-framework:latest

MAINTAINER Liu yongqiang@jfrog.com

ADD war/*.war /home/exec/tomcat/webapps/swampup.war

CMD /bin/bash -c cd /home/exec; /home/exec/tomcat/bin/catalina.sh run
