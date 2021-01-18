# Hazir API
Hazir's API is built on Python's Flask framework. There are 4-5 endpoints for various purposes. The main task of this API is to get students attendance info using get requests.

API has its own scraper which scrapes data from HU's PeopleSoft. To reduce the response time, we have optimized the API with multi-threading and selective parsing approaches. 

API is currently up and running on heroku's servers.

Main Endpoint

```https://hazirapi.herokuapp.com```

If you're a HU student, you can access your attendance data for the ongoing semester from this endpoint

```https://hazirapi.herokuapp.com/login?id=[your HUID]&pwd=[your password]```

Sample:

```https://hazirapi.herokuapp.com/login?id=ab01234&pwd=habibpass``` 

