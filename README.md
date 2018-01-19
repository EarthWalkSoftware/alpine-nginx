# EarthWalkSoftware/alpine-nginx  

The **earthwalksoftware/alpine-nginx** pre-built Docker image is available from [earthwalksoftware/alpine-nginx](https://hub.docker.com/r/earthwalksoftware/alpine-nginx/) at the EarthWalk Software presence on Docker Hub.

The **earthwalksoftware/alpine-nginx** docker image is based on the _NGINX version 1.13.8_ mainline (_edge_) in an  _Alpine Linux 3.7_ docker image (originally targeted at the _Alpine Linux 3.5_ docker image).  

----

#### Not A Stable Branch ####
 
This release is **NOT** based upon the _stable_ branch of **NGINX**.  Currently, there is no stable release of either version _1.12_ or version _1.13_ for _Alpine Linux_.  However, a docker container based upon **NGINX** _mainline 1.13.7_ in an _Alpine Linux 3.6_ docker container has been in use for several months.

----  

#### Not Official Release / Build  ####  

The **earthwalksoftware/alpine-nginx** docker image is **NOT** an official release of **NGINX**.  
  
The **official release** of **NGINX** is available from [NGINX, Inc.](https://github.com/nginxinc) at the following location:  
  https://github.com/nginxinc/docker-nginx  
  
The **official build** of **NGINX** is available from [NGINX, Inc.](https://github.com/nginxinc) at the following location:  
  https://hub.docker.com/_/nginx/  

----

#### So What Is It? ####  

As stated above, the **EarthWalkSoftware/alpine-nginx** web server is the **NGINX version 1.13.8** mainline (__edge__) docker source in an  __Alpine Linux 3.7__ docker image.  This repository contains only the mainline **version 1.13.8 Alpine Linux NGINX** code.

Why?  **NGINX** in Alpine Linux is a very small image, under 18 MB, yet is powerful enough to easily serve static web sites.  It's size and versatility make it easy to view **NGINX** as an __HTTP plug-in__ solution for many complex network service problems.

----  

#### Running NGINX ####  

General usage information for the **NGINX** image is available from the **NGINX** docker site:  

  https://hub.docker.com/_/nginx/  

Note: When using the instructions, replace the container name **nginx** with **earthwalksoftware/alpine-nginx**

------
### The name's too long
Change the name to a shorter name, such as _alpine-nginx_.

Pull the image down to the local docker host:  

    docker pull earthwalksoftware/alpine-nginx:latest  

Tag the new image with a shorter name (e.g. - *alpine-nginx:latest*):  

    docker tag earthwalksoftware/alpine-nginx:latest alpine-nginx:latest  

Remove the original image tag:  

    docker rmi earthwalksoftware/alpine-nginx:latest  

View docker images  

    docker images  

The *alpine-nginx:latest* image is now located on the local docker host.  The image may be accessed as

*alpine-nginx*

----  

#### A unique use for the alpine-nginx server  

To see a unique use of the alpine-nginx server, visit this article on the EarthWalk Softare alpine-nginx wiki: [pkgcache - a simple "plug in" for Docker build](https://github.com/EarthWalkSoftware/alpine-nginx/wiki/pkgcache----a-simple-%22plug-in%22-for-Docker-build)

----  

#### License ####  

The **EarthWalkSoftware/alpine-nginx** is controlled by the **NGINX License**, available at the following location  

  https://hub.docker.com/_/nginx/  

A copy of the License is available inside the running container as a text file in the root directory: ** /LICENSE**. and in the docker source on GitHub:

https://github.com/EarthWalkSoftware/alpine-nginx

----  
