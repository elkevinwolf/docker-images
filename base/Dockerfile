FROM alpine:3.13.5

# Install dependencies
RUN apk add --update git

# Install dotfiles
WORKDIR ${HOME}/.dotfiles
RUN git clone --recursive https://github.com/elkevinwolf/dotfiles .
RUN sh install.sh

WORKDIR ${HOME}
CMD [ "/bin/zsh" ]
