# Infra Setup

## Kafka
### Local 
Follow [this step](https://www.conduktor.io/get-started/) to setup local cluster which utilizes Dockerized Redpanda or just run `docker-compose -f docker-compose-kafka.yaml up`

### SAAS (Cloud)
For SAAS one, please take a look on:
- [Confluent](https://www.confluent.io/get-started/) - free $400 for the first 30 days without Credit Card required
- [Upstash](https://upstash.com/docs/introduction) - free forever
- [Redpanda](https://redpanda.com/try-redpanda) - free for the first 30 days

## OpenSearch
### Local
Follow [this step](https://opensearch.org/docs/latest/install-and-configure/install-opensearch/docker/#deploy-an-opensearch-cluster-using-docker-compose) to setup local cluster or just run `docker-compose -f docker-compose-opensearch.yaml up`

### SAAS (Cloud)
Please check [Bonsai.io](https://bonsai.io/). 