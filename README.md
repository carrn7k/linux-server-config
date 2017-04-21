
# Linux Server Project

Python Flask application hosted on an Amazonaws server

**IP ADDRESS:** 34.205.182.136
**URL:** http://ec2-34-205-182-136.compute-1.amazonaws.com

## Required Software

The back end of this application is built with Python's Flask
framework and utilizes Oauth2 via Google and Facebook for user
sign in and authentication. The app uses a Postgresql database; 
however, the database reads and writes are configured using
sqlalchemy. The front end uses some jQuery and the font-awesome
library.

## Configurations

This application is hosted via Amazon Lightsail and is configured
with Ubuntu. The SSH port has been changed from 22 to 2200. A 
firewall has been set up to only allow connections via the following
ports: 

* SSH/2200
* HTTP/80
* NTP/123

A user 'grader' has been added and given root privileges. The grader
is allowed access via an ssh key pair located in a .ssh/lightsail 
directory. 
