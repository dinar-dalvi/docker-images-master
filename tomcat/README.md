
##Steps to build

####On command line under the repo:

* docker build -t dinar/tomcat .
* run docker images and get the ID
* docker tag <ID> dinar/tomcat:v1
* docker images to check if the tag is applied
* docker login to dinar_docker repo on Docker Hub
* docker push dinar/tomcat:v1

######Everytime a new image is built please follow these steps. 
