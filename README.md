# NBA_Data
An ongoing project to pull and analyze data from the NBA API

This includes a backend MySQL Database that will store pulls from the NBA API (unfortunately that cannot be exposed here due to security issues).

In terms of work flow:
1) There is a webscraper that pulls various JSON results from the NBA API.
2) These are then stored locally and pushed into the MySQL database in GCP.
3) The MySQL database will be used to drive visualizations to make various dashboards using Panel and Altair.
