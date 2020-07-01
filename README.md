# BCpraca
Docker image is based on the  [Docker Image with Telegraf, InfluxDB and Grafana](https://github.com/philhawthorne/docker-influxdb-grafana) from [Phil Hawthorne](https://github.com/philhawthorne).

## Added node red to Dockerfile
```sh
npm install -g --unsafe-perm node-red
```
## Added Influx Nodes
```sh
npm install node-red-contrib-influxdb
```


