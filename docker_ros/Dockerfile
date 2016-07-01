# This is an auto generated Dockerfile for ros:kinetic-perception
# # generated from templates/docker_images/create_ros_image.Dockerfile.em
# # generated on 2016-05-13 23:38:52 +0000
FROM ros:kinetic-ros-base
MAINTAINER Tully Foote tfoote+buildfarm@osrfoundation.org

# install ros packages
RUN apt-get update && apt-get install -y \
    ros-kinetic-perception=1.3.0-0* 

RUN apt-get install -y net-tools  && apt-get install -y vim && apt-get install -y firefox 
    #&& rm -rf /var/lib/apt/lists/*
#RUN alias qtcreator='/home/jari/Qt/Tools/QtCreator/bin/qtcreator.sh'

RUN echo source /home/jari/kinetic_ws/devel/setup.bash >> ~/.bashrc


RUN apt-get install -y apt-transport-https 

#RUN apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys 379CE192D401AB61 && echo "deb https://dl.bintray.com/ornis/CloudCompare xenial main" | tee -a /etc/apt/sources.list && apt-get update --allow-unauthenticated && apt-get install -y cloudcompare 
