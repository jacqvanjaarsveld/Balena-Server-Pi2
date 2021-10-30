## This repository contains all the tools to build a balena container project designed to run on a Raspberry Pi Zero W.

This project is designed to build a Server device, running the Pi2.py file on a raspberry Pi, which creates and runs a Python Flask web-app. This device acts as a Server and Sink in a Server-client architecure, connecting to a second 'Client' device, which samples temprature and light level data (also inside a Balena container). The sensor samples collected by this device are sent to this server using Python TCP sockets.

The project contains a dockerfile template, which creates a Dockerfile used to install the libraries necessary for creating a Flask webserver, and to run the python script Pi2.py.

This project should print out the url of the Flask webserver, which can also be accessed on the Balena webportal.

The server-client interaction can be monitored from the Balena webportal.

This repository also contains a Youtube link to a video in which we demonstarte the functioning of our server.

## Authors: James Burness (BNRJAM019), Jacq van Jaarsveld (VJRJAC003)
