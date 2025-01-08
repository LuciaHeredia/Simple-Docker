# base image
FROM ubuntu:20.04

# ping package install
RUN apt-get update && apt-get install -y iputils-ping

# ping command
CMD [ "ping", "google.com"]
