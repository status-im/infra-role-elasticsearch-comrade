# Description

This role configures an [elasticsearch-comrade](https://github.com/moshe/elasticsearch-comrade) which is a Web UI for [ElasticSearch](https://www.elastic.co/).
It enables an easier overview of the health of the cluster and its management.

This role goes in tandem with [infra-role-elasticsearch](https://github.com/status-im/infra-role-elasticsearch).
You can find the documentation [here](https://moshe-1.gitbook.io/comrade/).

# Configuration

The only settings necessary to set are:
```yaml
es_comrade_clusters:
    cluster-a: ['host-01.a.prod:9200', 'host-02.a.prod:9200']
    cluster-b: ['host-01.b.prod:9200', 'host-02.b.prod:9200']
```
