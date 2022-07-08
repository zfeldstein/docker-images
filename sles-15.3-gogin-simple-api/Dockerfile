#https://hub.docker.com/repository/docker/zfeldstein/sles-15.3-gogin-simple-api
FROM registry.suse.com/bci/golang:1.17-12.4
COPY ./web-service-aarch64 /web-service
WORKDIR /
ENTRYPOINT ["/web-service"]
EXPOSE 8080

