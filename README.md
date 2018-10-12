# Page static with Docker and nginx

This is used to mount a static single page webpage using docker and nginx.

In the nginx configuration file there is the path `/*` which redirects all the requests to `index.html`, and another path `/api/*` which is to make that route work as a proxy.

## Build

Run `docker-compose build page_static`.

## Running

Run `docker-compose up`.