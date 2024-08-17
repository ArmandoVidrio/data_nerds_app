# data_nerds_app

## Steps to use the app:

1. Clone the repo
2. Build the images we are going to use with the command: `docker-compose build`
3. Initialize Airflow with the command: `docker-compose run airflow-init`
4. Then we run the other containers: `docker-compose up -d`
5. Finally, you can verify the status of the containers with: `docker-compose ps`
