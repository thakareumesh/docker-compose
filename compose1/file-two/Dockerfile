FROM centos:8
RUN yum update -y && yum install httpd httpd-tools -y
EXPOSE  80
COPY index.html /var/www/html
CMD     ["/usr/sbin/httpd","-D","FOREGROUND"]
