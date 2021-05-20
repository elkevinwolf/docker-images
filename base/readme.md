# `elkevinwolf/base`

Extension of the [`alpine`](https://hub.docker.com/_/alpine) image with some [extra binaries](https://github.com/elkevinwolf/dotfiles#binaries) and [ZSH configured as the default shell](https://github.com/elkevinwolf/dotfiles#oh-my-zsh).

## Run

```sh
docker run --rm -it elkevinwolf/base
```

## Extend

```docker
FROM elkevinwolf/base

# Your new instructions...
```
