FROM centos:7

RUN yum install httpd -y
RUN yum install net-tools -y
RUN yum install mariadb-server -y
WORKDIR /var/www/html

RUN mkdir nitesh
RUN echo test docker file > nitesh/test.html

CMD httpd -DFOREGROUND