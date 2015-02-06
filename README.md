oh-my-zsh keybase
==================

The [keybase command line tool](https://keybase.io/docs/command_line) lacks Tab completion for zsh (see [Issue #519](https://github.com/keybase/keybase-issues/issues/519) in the Keybase Bugtracker). So this'll provide auto-complete for keybase so you don't need to remember all those pesky arguments, designed to work with [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) but should work with others zsh setups too.

Installation
------------

To install put the `keybase` folder inside your `~/oh-my-zsh/custom/plugins/` directory and enable it within your .zshrc file.

Contributions
------------

Contributions welcome, open a PR. This is a pretty rough script, there are a few commands that could get some auto complete for sub-commands.

Version
-------

0.1

Integrity / GPG
---------------

I've signed the whole directory (in the `master` branch), you can check that with keybase
```
keybase dir verify
```

License
-------

MIT

