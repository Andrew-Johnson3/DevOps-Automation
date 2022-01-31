FROM openjdk AS build

WORKDIR /

LABEL "Name"="Harshit"

ADD ./server.java .

RUN javac server.java && mkdir server-data

CMD ["java", "Server"]
