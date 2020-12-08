# Base Image 
FROM ubuntu:16.04

# Maintainer of the Image
MAINTAINER Amit Vashist <amitvashist7@outlook.com>

# Update Apt Repo. 
RUN apt-get update

# Install Apache Packages 
RUN apt-get install apache2 -y 

# Excute the Service
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"] 
