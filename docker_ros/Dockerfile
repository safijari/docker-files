# This is an auto generated Dockerfile for ros:kinetic-perception
# # generated from templates/docker_images/create_ros_image.Dockerfile.em
# # generated on 2016-05-13 23:38:52 +0000
FROM ros:kinetic-ros-base
MAINTAINER Tully Foote tfoote+buildfarm@osrfoundation.org

RUN sed -i 's/^#\s*\(deb.*restricted\)$/\1/g' /etc/apt/sources.list

# install ros packages
RUN apt-get update && apt-get install -y \
    ros-kinetic-perception=1.3.0-0* 

RUN sed -i 's/^#\s*\(deb.*multiverse\)$/\1/g' /etc/apt/sources.list

RUN apt-get install -y apt-utils && apt-get install -y net-tools  && apt-get install -y vim && apt-get install -y firefox 

RUN apt-get update && apt-get install -y apt-transport-https 

RUN echo rosdep update >> /ros_entrypoint.sh

#RUN apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys 379CE192D401AB61 && echo "deb https://dl.bintray.com/ornis/CloudCompare xenial main" | tee -a /etc/apt/sources.list && apt-get update --allow-unauthenticated && apt-get install -y cloudcompare 
