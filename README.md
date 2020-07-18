# Dockerized

*[Read about it the Blog](https://sergeykibish.com/blog/how-docker-changed-my-workflow/)*

## Motivation

In some cases you do not want to install something directly on your OS, because it can create caches, hidden directories, etc. and you will loose track of it

## Installation

**OS**: Linux

To install:

```bash

git clone https://github.com/skibish/dockerized.git $HOME/dockerized

```

And add it to your path in `.<bash|zsh|etc>rc` file:

```bash

# You need to prepend it to path to overwrite what you have in your path
export PATH=$HOME/dockerized/bin:$PATH

# Or, to just add new functionality, add this
export PATH=$PATH:$HOME/dockerized/bin

```
