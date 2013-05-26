# autojump Puppet Module for Boxen
Don't know what autojump is? Read more about it [here](https://github.com/joelthelion/autojump).

[![Build Status](https://travis-ci.org/boxen/puppet-autojump.png)](https://travis-ci.org/boxen/puppet-autojump)

## Usage

```puppet
include autojump
```

After the install, you will also need to add the following line to your `~/.bash_profile` or `~/.zshrc` file (and remember
to source the file to update your current session):

    [[ -s `brew --prefix`/etc/autojump.sh ]] && . `brew --prefix`/etc/autojump.sh

## Required Puppet Modules

* `boxen`
* `homebrew`
* `stdlib`

