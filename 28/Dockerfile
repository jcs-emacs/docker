# This dockerfile is for jcs-emacs with 28
# VERSION 8.1.1
# Author: Jen-Chieh Shen <jcs090218@gmail.com>
# Command format: Instruction [arguments / command] ..

# Select operating system
FROM nixos/nix

# Install Emacs
RUN nix-channel --update
RUN nix-env -iA "emacs-28-1" -f "https://github.com/purcell/nix-emacs-ci/archive/master.tar.gz"

# Install jcs-emacs
RUN nix-env --install git
RUN git clone --depth 1 https://github.com/jcs-emacs/jcs-emacs.git ~/.emacs.d

ENV TERM xterm-256color
WORKDIR /root
