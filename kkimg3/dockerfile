
FROM  fedora
 
MAINTAINER kk.sharma9597@gmail.com 

RUN dnf install httpd -y

ADD pages/kk.html /var/www/html/index.html

EXPOSE 80

ENTRYPOINT httpd -DFOREGROUND 



