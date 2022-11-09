FROM centos:7

RUN yum install python3 -y

RUN mkdir /code
COPY  1.py /code


ENTRYPOINT [ "python3" ]
CMD [ "/code/1.py" ]

