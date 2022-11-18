FROM centos:7


COPY ./run.sh /run.sh

RUN chmod +x /run.sh
RUN /run.sh

ENTRYPOINT [ "/bin/bash" ]
#CMD [ "/run.sh" ]
