---
title: Examples
---
Shown examples use official Docker images. Examples also show links to download the files, to provide easier deployment.

> Example deployments use insecure credentials, you **MUST** change them

## PostgreSQL
This example shows how the backend can be configured using a PostgreSQL database.

- [Download: docker-compose.yml](postgres-docker-compose.yml)

{{< highlight-resource file="postgres-docker-compose.yml" lang="yml" >}}

## Nginx HTTP
This example allows you to access both the frontend and backend over the standard HTTP port (80).

- [Download: docker-compose.yml](nginx-http-docker-compose.yml)
- [Download: nginx.conf](nginx-http-nginx.conf)

{{< highlight-resource file="nginx-http-docker-compose.yml" lang="yml" >}}
{{< highlight-resource file="nginx-http-nginx.conf" lang="properties" >}}
