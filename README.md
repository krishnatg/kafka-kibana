# Simple benthos pipeline to visualize data in Kafka using Elasticsearch + Kibana

ref: https://github.com/Jeffail/benthos

Use `docker-compose-kafka-infra.yaml` to start a local kafka setup first(one broker, one ZK, one schema registry).

If using your own kafka infra, ignore the above step and just use `docker-compose.yaml` after modifying the
values of `INPUT_KAFKA_BALANCED_ADDRESSES` and `INPUT_KAFKA_BALANCED_TOPICS` in the file.
