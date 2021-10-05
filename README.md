# Grafana Dashboard for Browserstack Automate

## Requirements
- Docker

## Installation

Start the Docker by running the following command:

 ```sh
docker-compose up -d
```

## Plugin Installation

Use the grafana-cli tool to install JSON API & Infinity plugin from the commandline:

 ```sh
grafana-cli plugins install marcusolsson-json-datasource
```

 ```sh
 grafana-cli plugins install yesoreyeram-infinity-datasource
 ```
## Add Browserstack Usename & Accesskey to json 

Identify your BrowserStack username and access key from the [BrowserStack Automate Dashboard](https://automate.browserstack.com/) and add them to the json file 


## Import Dashboard

To import a dashboard click the + icon in the side menu, and then click Import and select Browserstack_Dashboard.json file 

<img width="800" src="https://user-images.githubusercontent.com/79913684/135970160-fd3c3f08-f9b7-413e-8a6a-aad0a3c7c1d8.png">

## View Dashboard

You can view the browserstack dashboard under Dashboards 

<img width="800" alt="Screenshot 2021-10-05 at 11 45 33 AM" src="https://user-images.githubusercontent.com/79913684/135970325-ab41ee44-1818-4332-8e7a-a34c6a62698a.png">

