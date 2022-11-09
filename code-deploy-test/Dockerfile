FROM centos:7

MAINTAINER Nitesh Jain <jain.nitesh964@gmail.com>
RUN yum install python3 -y

RUN mkdir /code
COPY  1.py /code
COPY  2.py /code
COPY  3.py /code


ENTRYPOINT [ "python3" ]
CMD [ "/code/1.py" ]

