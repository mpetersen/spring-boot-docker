# Spring-Boot Docker Demo Project

This demo project shows how to run a Spring-Boot application inside a docker container - including hot 
reloading classes.

# Setup

To run this project change into the `docker/` directory and run `docker-compose up`. Then you can access the 
application by calling `http://<IP address of your docker container>:8080`.  

	# cd docker/
	# docker-compose up
	
# Check hot-reloading classes

Now change something in the `Example.java` class, e.g. replace "Hello World!" with something else
and refresh the browser.