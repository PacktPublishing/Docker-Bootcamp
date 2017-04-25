# Docker Bootcamp
This is the code repository for [Docker Bootcamp](https://www.packtpub.com/virtualization-and-cloud/docker-bootcamp?utm_source=github&utm_medium=repository&utm_content=9781787286986) By Packt. It contains all the supporting project files necessary to work through the book from start to finish.

## About the book

Docker allows you to create a robust and resilient environment to generate portable, composable, scalable, and stable application containers.

The book starts by installing the core Docker Engine on MacOS, Windows 10 and Linux desktops. We will then define multi-container applications and understand the advantages of using containers locally. Once this is done, we will deploy containers on a single Docker host which is publicly accessible. Furthermore, we will learn how to deploy and configure a Docker Swarm cluster and explore networking and storage third-party plugins to extend the core Docker functionality. Towards the end, the book will demonstrate how to monitor and troubleshoot day-to-day problems in addition to various real world examples of container deployments.

##Instructions and Navigation

All of the code is organized into folders, code files are available for Chapter 2, 3, 4, 5 and 6. For example, Chapter 1. 

You will see code something similler to the following:

    docker container run -d \
      --name mysql \
       -e MYSQL_ROOT_PASSWORD=wordpress \
       -e MYSQL_DATABASE=wordpress \
       mysql
     
     
### Note
