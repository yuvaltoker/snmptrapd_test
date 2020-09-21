FROM polinux/snmpd
COPY ./go /
COPY ./instructions.sh /
RUN chmod +x /instructions.sh
RUN echo "hey, you're here" >> /etc/hosts.allow
ENTRYPOINT ["/bin/sh", "/instructions.sh"]

