# opendistro-docker-compose

Before starting opendistro docker-compose, please generate SSL certificates [Instructions here](certs/README.md)


To start opendistro-docker-compose simply run:

```
sudo sysctl -w vm.max_map_count=262144; docker-compose up -d
```
