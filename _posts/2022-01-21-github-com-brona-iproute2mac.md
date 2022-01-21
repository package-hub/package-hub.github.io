---
title: iproute2mac
categories: ['python']
---
## [iproute2mac](https://github.com/brona/iproute2mac)

### CLI wrapper for basic network utilites on Mac OS X inspired with iproute2 on Linux systems - ip command.


A) Using [Homebrew](http://brew.sh):

    # [Optional] Install Homebrew first - see http://brew.sh for more options
    $ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

    # Install iproute2mac
    $ brew install iproute2mac

B) Manual installation:

    $ curl --remote-name -L https://github.com/brona/iproute2mac/raw/master/src/ip.py
    $ chmod +x ip.py
    $ mv ip.py /usr/local/bin/ip

