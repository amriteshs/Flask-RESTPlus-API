## Flask-RESTPlus-API

Developed a Flask-RESTPlus data service that allows a client to read some publicly available economic indicator data for countries around the world, and allow the consumers to access the data through a REST API.

Source URL: http://api.worldbank.org/v2/
Documentations on API Call Structure: https://datahelpdesk.worldbank.org/knowledgebase/articles/898581-api-basic-call-structure

The World Bank indicators API provides 50 year of data over more than 1500 indicators for countries around the world.
1. List of indicators can be found at: http://api.worldbank.org/v2/indicators
2. List of countries can be found at: http://api.worldbank.org/v2/countries

Database used: SQLite

The data service performs the following operations:
1. Import a collection from the data service.
2. Delete a collection with the data service.
3. Retrieve the list of available collections.
4. Retrieve a collection.
5. Retrieve economic indicator value for given country and a year.
6. Retrieve top/bottom economic indicator values for a given year
