---
title: Setup
---
This section of the docs is designed for admins who wish to setup Note Mark. Here are some general notes:

- The official and recommended way of installing and managing the services is to use Docker
- There are two main services: backend and frontend
- the "backend" provides the web API for the frontend and other third-party apps to access the service
    - requires either SQLite or a PostgreSQL server
- the "frontend" provides a SPA that allows for online access of the backend
    - basically just some static files once built
