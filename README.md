# vastdb-streaming-demo

## Dependencies

- Recent version of Docker Compose.

## Setup

### Streaming Ingest

- Install and Run [Kafka](https://github.com/snowch/vast-docker-compose-examples/tree/main/kafka)
- Install and Run [NiFi](https://github.com/snowch/vast-docker-compose-examples/tree/main/vastdb-nifi)
- Upload [NiFi Flow](./Streaming_Ingest.json), configure:
  - AWS Credentials and Enable
  - Vast DB Endpoint (URL)
  - Kafka Endpoints (URL)

### Reporting

- Install and Run [Superset and Trino](https://github.com/snowch/vast-docker-compose-examples/tree/main/vastdb-superset)

## Running

Coming soon ...
