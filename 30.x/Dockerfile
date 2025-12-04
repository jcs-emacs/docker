# This dockerfile is for jcs-emacs with 30.x
# VERSION 9.2.0
# Author: Jen-Chieh Shen <jcs090218@gmail.com>
# Command format: Instruction [arguments / command] ..

# Select operating system
FROM nixos/nix

# Install Emacs
RUN nix-channel --update
RUN nix-env -iA "emacs-30-2" -f "https://github.com/purcell/nix-emacs-ci/archive/master.tar.gz"

# Install jcs-emacs
RUN git clone --depth 1 https://github.com/jcs-emacs/jcs-emacs.git ~/.emacs.d --branch 9.2.0 --recursive

ENV TERM xterm-256color
WORKDIR /root
