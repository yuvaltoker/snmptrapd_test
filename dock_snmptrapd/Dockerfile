FROM polinux/snmpd
ADD server.py /
ADD message.py
RUN pip install redis
ENTRYPOINT [ "python", "./server.py" ]

