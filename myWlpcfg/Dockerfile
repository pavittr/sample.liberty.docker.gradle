FROM websphere-liberty:latest

MAINTAINER Ross Pavitt

ADD ./servers/defraultServer /opt/ibm/wlp/usr/servers/defaultServer/
RUN apt-get update; apt-get install -y curl
RUN /opt/ibm/wlp/bin/installUtility install  --acceptLicense /opt/ibm/wlp/usr/servers/defaultServer/server.xml


COPY ./startup.sh /opt/startup.sh

CMD ["/opt/startup.sh"]
