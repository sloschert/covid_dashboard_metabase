# covid_dashboard_metabase
Daily updated metabase dashboards with analysis regarding Covid19 in the federal states of Germany.

Data source: Robert-Koch Institut (RKI)

Data is stored and daily updated to a PostgreSQL-database on an AWS RDS server.
Data is analysed and presented with the BI tool Metabase, which runs inside a Docker
Container on an AWS EC2 machine.

[Link](http://ec2-3-123-231-79.eu-central-1.compute.amazonaws.com/public/dashboard/85b0b7de-6aa1-4a0c-a57e-d1e3ad6cc28e) to a dashboard with information on the current situation in Friedrichshain-Kreuzberg, Neukölln and Berlin.

[Link](http://ec2-3-123-231-79.eu-central-1.compute.amazonaws.com/public/dashboard/2ab3b88d-05ff-4a04-9097-187d787ccf6d) to a dashboard with information on the current situation in Berlin. The user can chose which district they want to examine. 

[Link](http://ec2-3-123-231-79.eu-central-1.compute.amazonaws.com/public/dashboard/96406184-1318-449b-8b31-655276cbacaa) to a dashboard with information on the current situation in Main-Spessart, Würzburg and Bavaria.
