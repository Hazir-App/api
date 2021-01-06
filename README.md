# Hazir API
Hazir's API is built on Python's Flask framework. There are 4-5 endpoints for various purposes. The main task of this API is to get students attendance info using get requests.

API has its own scraper which scrapes data from HU's PeopleSoft. To reduce the response time, we have optimized the API with multi-threading and selective parsing approaches. 

API is currently up and running on heroku's servers.

Main Endpoint

```https://hazirapi.herokuapp.com```
