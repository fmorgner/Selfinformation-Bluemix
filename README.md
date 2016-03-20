# Selfinformation-Bluemix

This a port of the CDAR Selfinformation Application from GAE & Jetty to IBM Liberty for running on IBM Bluemix

## Requirements

* Maven 3 (building)
* IBM Bluemix account (deployment)
* Cloud Foundry CLI tools (deployment)

## Configuration

Change the 'host' property in 'manifest.yml'

## Building & running

To build just run:

~~~
$ mvn install
~~~

To run the server locally:

~~~
$ mvn liberty:run-server
~~~

and to deploy to bluemix:

~~~
$ cf push
~~~
