# Phaser3 Docker Quickstart

Provides a pre-configured Phaser3 environment (webserver is Apache).

1.  To setup first install [Docker-Desktop / Docker](https://www.docker.com/products/docker-desktop).

2.  Then in the directory containing this `README` run the following from your shell of choice:

`docker-compose up -d`

3.  Wait for the containers to be downloaded, built and the default network to be setup.

4.  Once complete, visit `localhost:80`.  You should see the following:

![screenshot](./www/resources/images/screenshot.png)

Congrats!  Your setup and ready to start developing with Phaser3, look in `./www/index.html` for the Phaser3 test file shown.  Note that everything in `./www` is shared into the Docker container's webserver and moutned at the site root (ie: `localhost/(HERE)`).