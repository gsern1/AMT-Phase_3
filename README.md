# AMT-Phase_1-Drabble-Serneels

## Introduction

This repo contains artifacts to illustrate the high-level Java EE development cycle:
Using Docker, it deploys a GlassFish application server, the reference implementation of Java EE.
The server takes advantage of the auto deploy feature to makes a simple web app available at a specified URL.


## Quick start

Assuming that you have installed **docker** and **docker-compose** on your machine, move to the `topology-amt` directory and fire up docker-compose to start the glassfish app servers:

```
cd topology-amt
docker-compose up --build
```

## Access the webapp

To access the webapp you must follow the link http://127.0.0.1:8080/AMT-Webapp-Welcome-1.0-SNAPSHOT/ if you're using 'Docker for Mac'/'Docker for PC' or http://192.168.99.100:8080/AMT-Webapp-Welcome-1.0-SNAPSHOT/ if you are using the Docker Machine.

## Access the administration console of GlassFish

The administration console is accessible at http://127.0.0.1:4848 if you're using 'Docker for Mac'/'Docker for PC' or http://192.168.99.100:4848 if you are using the Docker Machine.