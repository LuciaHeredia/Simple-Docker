# base image
FROM ubuntu:20.04

# package install 
RUN apt-get update && apt-get install -y nano

# setting & creating working directory
WORKDIR /app

# copy file into container(at: /app)
COPY textfile.txt /app

# open file
CMD ["nano", "textfile.txt"]