# This dockerfile is for Centaur Emacs with snapshot
# VERSION 8.1.1
# Author: Jen-Chieh Shen <jcs090218@gmail.com>
# Command format: Instruction [arguments / command] ..

# Base image to use
FROM silex/emacs

# Install jcs-emacs
RUN git clone --depth 1 https://github.com/jcs-emacs/jcs-emacs.git ~/.emacs.d

ENV TERM xterm-256color
WORKDIR /root
