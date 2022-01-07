FROM alpine:3.15.0

# Set home directory
ENV HOME /root

# Install dependencies
RUN apk add --update git

# Install dotfiles
WORKDIR ${HOME}/.dotfiles
RUN git clone --recursive https://github.com/elkevinwolf/dotfiles .
RUN sh install.sh

WORKDIR ${HOME}
CMD [ "/bin/zsh" ]
