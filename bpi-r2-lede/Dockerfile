#
# BPI R2 LEDE Ubuntu Build Environment Dockerfile
#
# Pull base image.
FROM ubuntu:16.04

# Upgrade System
RUN apt-get update
RUN apt-get upgrade -y

# Install required packages
RUN apt-get install -y build-essential libssl-dev git libncurses5-dev unzip gawk zlib1g-dev flex vim curl wget bison python

# Set environment variables.
ENV HOME /root
ENV FORCE_UNSAFE_CONFIGURE 1

# Create Working Directory
RUN mkdir -p /source
WORKDIR /source

