# Testing dbt in Cloud Composer in GCP

The purpose of this repo is to build a base Docker image containing the install for dbt. This Docker image will be stored in Artifact Registry.
There will be a second Docker image built containing the actual code for running dbt transformations.
The Docker images are split out this way to improve the creation time of the Docker images.
Additionally, there is only one image for managing the dbt version, which will not change very often. The dbt code repo Docker image will change more frequently.