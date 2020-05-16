# Elastic Cluster

This is a sample docker compose network that builds a multiple node elastic
cluster using Elasticsearch version 7.x


## Run
`docker-compose up -d`
Will raise three nodes, all are master eligible.  Elasticsearch data directory uses
volumes through docker compose.


## TODO
* More nodes?
* Master specific nodes, data specific nodes (more sophisticated cluster setup)
