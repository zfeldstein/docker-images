#https://hub.docker.com/repository/docker/zfeldstein/sles-15.3-gogin-simple-api
FROM registry.suse.com/bci/bci-base:15.3
COPY ./web-service /web-service
WORKDIR /
ENTRYPOINT ["/web-service"]
EXPOSE 8080

