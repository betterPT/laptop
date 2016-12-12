Laptop
======

Laptop is a script to set up an macOS laptop for web development.

It can be run multiple times on the same machine safely.
It installs, upgrades, or skips packages
based on what is already installed on the machine.

Install
-------

Download, review, then execute the script:

```sh
curl --remote-name https://raw.githubusercontent.com/thoughtbot/laptop/master/mac
less mac
sh mac 2>&1 | tee ~/laptop.log
```

Post-Install Directions
-----------------------

After you login to your machine, please do the following:

1. [Setup git and Github](https://help.github.com/articles/set-up-git/)
2. Login to Xcode and/or Android Studio and add your accounts
3. Configure 1password

Extras
------

The default shell has been set to zsh and the basic [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) has been added.  To modify your `~/.zshrc`, add plugins or themes see [here](https://github.com/robbyrussell/oh-my-zsh#plugins).
