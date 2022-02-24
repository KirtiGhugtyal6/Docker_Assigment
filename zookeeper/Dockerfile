FROM openjdk:8-jre-slim

WORKDIR /kafka-docker

ADD kafka/ /kafka-docker/

EXPOSE 2181

CMD ./bin/zookeeper-server-start.sh config/zookeeper.properties


