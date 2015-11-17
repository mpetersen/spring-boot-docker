# Spring-Boot Docker Demo Project

This demo project shows how to run a Spring-Boot application inside a docker container - including 
hot reloading classes.

## Running and Debugging

Change into the `docker` directory. This directory contains the `Dockerfile` and `docker-compose` 
files, and two shell scripts for running or debugging the application.

To start the container normally, start the `./run.sh` script.

To debug the application, start the `./debug.sh` script and connect the remote debugging session to 
port `5005` of the container (get the IP of your docker-machine by running 
`docker-machine ip <name-of-machine>`).
	
## Check hot-reloading classes

Now change something in the `Example.java` class, e.g. replace "Hello World!" with something else
and refresh the browser.

## System requirements

You need to have a running Docker installation and docker-compose installed to run this demo. It 
also assumes, that you are using any kind of IDE - it works with Eclipse..
