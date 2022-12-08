FROM ansible-image

COPY sshrun.sh /root/
EXPOSE 22

ENTRYPOINT ["/bin/sh", "/root/sshrun.sh"]
#CMD ["/usr/sbin/sshd", "-D"]


