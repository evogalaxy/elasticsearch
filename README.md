# elasticsearch

Install Elasticsearch.

## Tasks

Tasks are extracted in several files, included in `tasks/main.yml` :

* `java.yml` : install Java 8 ;
* `elasticsearch.yml` : install packages ;
* `configuration.yml` : configure the service;
* `bootstrap_checks.yml` : deal with bootstrap checks;
* `datadir.yml` : data directory customization ;
* `tmpdir.yml` : temporary directory customization ;

## Available variables

* `elasticsearch_cluster_name`: cluster name ;
* `elasticsearch_node_name`: node name, defaults to hostname ;
* `elasticsearch_network_host`: which interfaces to bind to ;
* `elasticsearch_network_publish_host`: which interface to publish ;
* `elasticsearch_custom_datadir`: custom datadir
* `elasticsearch_custom_tmpdir`: custom tmpdir