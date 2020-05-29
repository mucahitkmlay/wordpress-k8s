# Wordpress-application-in-kubernetes-with-Cloud-SQL-as-database
1) Step 1

- Enable the API

2) Step 2

- Create a service account

- Role, select Cloud SQL > Cloud SQL Client


3) Step 3

- Create the user account for the proxy

4) Step 4

- git clone https://github.com/mucahitkmlay/Magento2-application-in-kubernetes-with-Cloud-SQL-as-database.git

5) Step 5

- Get instance connection name

- gcloud sql instances list

- gcloud beta sql instances describe [SQL INSTANCE NAME]| grep connection

6) Step 6 

- cd PATH/Magento2-application-in-kubernetes-with-Cloud-SQL-as-database

- kubectl apply -k ./

- Open domain or IP adress


Learn more...
https://medium.com/@mucahit_kmlay/magento2-app-in-kubernetes-with-google-sql-as-database-d8e3a53705ee
