FROM centos:7

RUN yum install httpd -y
RUN yum install net-tools wget -y
RUN yum install https://repo.mysql.com//mysql57-community-release-el7-7.noarch.rpm -y
RUN yum-config-manager --enable mysql57-community -y
RUN yum install mysql-server -y
WORKDIR /var/www/html

RUN mkdir nitesh
RUN echo test docker file > nitesh/test.html

CMD httpd -DFOREGROUND
CMD ["mysqld"]