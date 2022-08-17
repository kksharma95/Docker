
FROM  fedora
 
MAINTAINER kk.sharma9597@gmail.com 

RUN dnf install httpd -y

COPY pages/kk.html /var/www/html/index.html

EXPOSE 80

CMD httpd -DFOREGROUND 



