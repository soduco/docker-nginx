This is a dockerized Nginx modified version to work with the "catalog" repo in SODUCO organization

The only difference is that the nginx config file includes commands outside the "http" block ("stream" was needed for TCP connexion)


Original Readme:
# About this Repo

This is the Git repo of the official Docker image for [nginx](https://registry.hub.docker.com/_/nginx/). See the
Hub page for the full readme on how to use the Docker image and for information
regarding contributing and issues.

The full readme is generated over in [docker-library/docs](https://github.com/docker-library/docs),
specifically in [docker-library/docs/nginx](https://github.com/docker-library/docs/tree/master/nginx).

The changelog for NGINX releases is available at [nginx.org changes page](https://nginx.org/en/CHANGES).
