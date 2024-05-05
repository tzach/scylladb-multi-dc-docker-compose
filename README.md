Example for running ScyllaDB as a multi DC deployment with Docker Compose

### Run

```
docker up
docker exec -it scylla-node1 nodetool status
docker exec -it scylla-node1 cqlsh
```
