# springbootdocker

Microservice with Spring boot and Docker
One Paragraph of project description goes here


Getting Started
---------------
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.


Prerequisites
-------------
you should install Java >=8 and Docker


Installing
----------

git clone https://github.com/julianmarcelolopez/springbootdocker


MVN
---
mvn clean
mvn install


COMANDOS DOCKER 
---------------

docker build -t spring_boot_docker {PATH}

docker run -d -p 8080:8080 spring_boot_docker


TEST
----

http://localhost:8080/greeting?name=julian
