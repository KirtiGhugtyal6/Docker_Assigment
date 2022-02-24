FROM openjdk:8-jre-slim

WORKDIR /kafka-docker

ADD kafka/ /kafka-docker/

ENTRYPOINT ["./bin/kafka-console-producer.sh","--bootstrap-server","server:9092","--topic"]

CMD [ "test" ]
