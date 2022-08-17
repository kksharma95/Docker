FROM centos 

MAINTAINER kk.sharma9597@gmail.com
# this is dynamic variable we can replace the value during build time 
ARG 	x=ftp
ARG 	y=kk.html

RUN yum update -y
RUN yum upgrade -y

RUN yum install $x -y 
COPY $y /var/www/html/index.html



