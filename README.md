# Testing dbt in Cloud Composer in GCP

The purpose of this repo is to build code to test Cloud Composer in GCP with dbt.
There is a Dockerfile to build a Docker image containing dbt. This Docker image will be stored in Artifact Registry.
There is a folder called "dag" for storing the Airflow code to manage the dbt job.
the "dbt-project" folder contains all the data transformations.