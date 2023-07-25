1. ## sudo aws s3 sync dummy-web-files-001 /home/ec2-user ##

2. ## sudo aws s3 sync fleetcart-web-files-001 /var/www/html ##

3. ## sudo aws s3 sync s3://rentzone-app-001 /var/www/html


The above are the webfiles for the dynamic app "1 and 2" are for fleetcart dynamic app whereas '3' is for Rentzone, car rental dynamic app.


The 2 .sql script are for databases of the diff application and has to be migrated to the database of each app. rentzone.sql migrated to rentzone app database and fleetcart.sql migrated to fleetcart application db.

