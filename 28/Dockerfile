# This dockerfile is for Centaur Emacs with 27
# VERSION 8.1.1
# Author: Jen-Chieh Shen <jcs090218@gmail.com>
# Command format: Instruction [arguments / command] ..

# Base image to use
FROM ubuntu:latest
ARG DEBIAN_FRONTEND=noninteractive

# Commands to update the image
RUN cp /etc/apt/sources.list /etc/apt/sources.list.bak
RUN sed -i "s/ports.ubuntu.com/mirrors.aliyun.com/g" /etc/apt/sources.list
RUN apt-get update
RUN apt-get upgrade -y
RUN apt-get install -y software-properties-common git

# Install Centaur Emacs
RUN add-apt-repository -y ppa:kelleyk/emacs
RUN apt-get update
RUN apt-get install -y emacs27-nox
RUN git clone --depth 1 https://github.com/jcs-emacs/jcs-emacs.git ~/.emacs.d

ENV TERM xterm-256color
WORKDIR /root
