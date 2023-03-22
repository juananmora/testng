Prueba para ejeuctar desde Jenkins - ALM Octane

Docker images for the Selenium Grid Server
The project is made possible by volunteer contributors who have put in thousands of hours of their own time, and made the source code freely available under the Apache License 2.0.

These Docker images come with a handful of tags to simplify its usage, have a look at them in one of our releases.

To get notifications of new releases, add yourself as a "Releases only" watcher.

These images are published to the Docker Hub registry at Selenium Docker Hub.


 mvn -s settings.xml clean package

 docker-compose -f docker-compose-v3.yml up -d --scale chrome=3 --scale firefox=2
 


