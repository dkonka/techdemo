from fnndsc/ubuntu-python3:latest

#env PATH=$PATH:/usr/local/bin

COPY . /opt/

WORKDIR /opt
RUN sh install.sh
CMD ["app.py"]
ENTRYPOINT ["/usr/local/bin/python"]