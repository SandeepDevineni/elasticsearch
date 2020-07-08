

WORKDIR /opt/elasticsearch_client

COPY --from=builder /opt/elasticsearch_client/target/elasticsearch_client-1.0-SNAPSHOT-jar-with-dependencies.jar elasticsearch_client-1.0-SNAPSHOT.jar

USER 65534

ENV _JAVA_OPTIONS=-Djava.io.tmpdir=/tmp

CMD ["/opt/elasticsearch_client/elasticsearch_client-1.0-SNAPSHOT.jar"]