FROM openjdk AS build

WORKDIR /

LABEL "Name"="Harshit"

ENV IP=180.10.0.10

ADD ./Client.java .

RUN javac client.java 

CMD java Client ${IP}
