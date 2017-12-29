
##Steps to build

This container is built for a specific demo purpose (java web app + jmeter)

####On command line under the repo:

* docker build -t dinar/postgres .
* run docker images and get the ID
* docker tag <ID> dinar/postgres:v1
* docker images to check if the tag is applied
* docker login to dinar_docker repo on Docker Hub
* docker push dinar/postgres:v1

######Everytime a new image is built please follow these steps. 
