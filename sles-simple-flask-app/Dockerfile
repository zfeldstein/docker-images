#https://hub.docker.com/repository/docker/zfeldstein/sles-simple-flask-app
FROM registry.suse.com/bci/bci-base:15.3
COPY . /app
WORKDIR /app
RUN zypper -n in curl python3 python3-pip && \
      pip install -r requirements.txt
ENTRYPOINT ["/usr/bin/python3", "app.py"]
EXPOSE 5000
