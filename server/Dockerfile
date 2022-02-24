FROM openjdk:8-jre-slim

WORKDIR /kafka-docker

ADD kafka/ /kafka-docker/

EXPOSE 9092

CMD [ "./bin/kafka-server-start.sh","config/server.properties" ]
