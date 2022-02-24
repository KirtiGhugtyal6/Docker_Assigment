FROM openjdk:8-jre-slim

WORKDIR /kafka-docker

ADD kafka/ /kafka-docker/

ENTRYPOINT [ "./bin/kafka-console-consumer.sh","--bootstrap-server","server:9092","--from-beginning","--topic" ]

CMD [ "test" ]
