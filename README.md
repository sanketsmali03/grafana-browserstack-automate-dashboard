# Grafana Dashboard for Browserstack Automate

## Requirements
- Docker

## Installation

Start the Docker by running the following command:

 ```sh
docker-compose up -d
```

## Plguin Installation

Use the grafana-cli tool to install JSON API & Infinity plugin from the commandline:

 ```sh
grafana-cli plugins install marcusolsson-json-datasource
```

 ```sh
 grafana-cli plugins install yesoreyeram-infinity-datasource
 ```
