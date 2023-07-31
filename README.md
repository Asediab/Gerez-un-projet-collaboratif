Back  
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=asediab_Gerez-un-projet-collaboratif-back&metric=coverage)](https://sonarcloud.io/summary/new_code?id=asediab_Gerez-un-projet-collaboratif-back)  
[![Quality gate](https://sonarcloud.io/api/project_badges/quality_gate?project=asediab_Gerez-un-projet-collaboratif-back)](https://sonarcloud.io/summary/new_code?id=asediab_Gerez-un-projet-collaboratif-back)  

Front   
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=asediab_Gerez-un-projet-collaboratif-front&metric=coverage)](https://sonarcloud.io/summary/new_code?id=asediab_Gerez-un-projet-collaboratif-front)  
[![Quality gate](https://sonarcloud.io/api/project_badges/quality_gate?project=asediab_Gerez-un-projet-collaboratif-front)](https://sonarcloud.io/summary/new_code?id=asediab_Gerez-un-projet-collaboratif-front)
# BobApp
Docker Hub: https://hub.docker.com/search?q=asediaboli  

Clone project:

> git clone XXXXX

## Front-end 

Go inside folder the front folder:

> cd front

Install dependencies:

> npm install

Launch Front-end:

> npm run start;

### Docker

Build the container:

> docker build -t bobapp-front .  

Start the container:

> docker run -p 8080:8080 --name bobapp-front -d bobapp-front

## Back-end

Go inside folder the back folder:

> cd back

Install dependencies:

> mvn clean install

Launch Back-end:

>  mvn spring-boot:run

Launch the tests:

> mvn clean install

### Docker

Build the container:

> docker build -t bobapp-back .  

Start the container:

> docker run -p 8080:8080 --name bobapp-back -d bobapp-back 