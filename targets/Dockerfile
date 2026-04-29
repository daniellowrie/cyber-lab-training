# Use a VERY SMALL Linux base image
FROM alpine:latest

# Install basic tools we might need for lab work
RUN apk add --no-cache bash curl openssh-client python3 && ln -sf python3 /usr/bin/python

# Just keep the container running so we can use it as a target
CMD ["tail", "-f", "/dev/null"]
