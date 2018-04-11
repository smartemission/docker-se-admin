# Smart Emission Admin Web App

Admin web app for the SE platform.

## Hosting

The Docker Image is hosted as: 
[smartemission/se-admin at DockerHub](https://hub.docker.com/r/smartemission/se-admin).

It is accessed/viewed via `*.smartemission.nl/admin`, e.g. https://pdok.smartemission.nl/admin.

## Environment

The following environment vars need to be set, either via `docker-compose` or
Kubernetes.

|Environment Variable|Default
|---|---
|ADMIN_LOG_LEVEL|10 (debug)

## Architecture

The image contains a simple Flask webapp running in gunicorn WSGI server.
The app runs the Admin static webpages for now, but can be expanded in future
with more dynamic info.

## Links

* SE Platform doc: http://smartplatform.readthedocs.io/en/latest/
