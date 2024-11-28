# UAAP Stats Scraper Web App
A Java Spring web app that scrapes data from livestats.ph and saves to a databases that can also be downloaded in csv format.
Consists of these microservices:
- UAAP Stats Scraper ([_runardo/uaapstatscraper:v2_](https://hub.docker.com/repository/docker/runardo/uaapstatscraper))
  - A REST API that scrapes data from the website
- UAAP Stats Data
  - A CRUD REST API for the UAAP Stats ([_runardo/uaapstatsdata:v2_](https://hub.docker.com/repository/docker/runardo/uaapstatsdata))
 
## How to use this chart
### 1. Install Helm chart
### 2. Create a kubernetes cluster
### 3. Run the chart into the kubernetes cluster
` helm install <name> <path/to/chart/uaapstatscraperapp> `

