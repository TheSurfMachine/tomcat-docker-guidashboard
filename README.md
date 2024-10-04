# This repo is unaltered except for this readme file.
* This repo was built and has the web server admin welcome page already setup.
* This gives us a pretty gui welcome page, instead of seeing a default "Error 404" page.
* I did not rebuild the .war file, setup login page or anything else.
* Intended Use: Only to git clone the repo, use docker build command, and use docker run command to launch war file, and view tomcat web server page.


# docker-tomcat-tutorial
A basic tutorial on running a web app on Tomcat using Docker

See tutorial here - https://www.softwareyoga.com/docker-tomact-tutorial/

# Steps
* Install [Docker](https://docs.docker.com/install/).
* Clone this repository - $git clone https://github.com/softwareyoga/docker-tomcat-tutorial.git
* cd 'docker-tomcat-tutorial'
* $docker build -t mywebapp .
* $docker run -p 80:8080 mywebapp
* http://localhost:80

# Links
[Sample Tomcat web app](https://tomcat.apache.org/tomcat-8.0-doc/appdev/sample/)
