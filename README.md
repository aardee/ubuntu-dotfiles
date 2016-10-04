# ubuntu-dotfiles

## Installation

### Using Git and the bootstrap script

The repository can be cloned wherever you want. The bootstrap script will [git]  pull in the latest version and _overwrite_ the files to your home folder.

```bash
git clone --recursive https://github.com/aardee/ubuntu-dotfiles.git && cd ubuntu-dotfiles && source bootstrap.sh
```

To update, `cd` into the local `ubuntu-dotfiles` repository and execute:

```bash
source bootstrap.sh
```

The confirmation prompt can be avoided by executing:

```bash
set -- -f; source bootstrap.sh
```

### Custom path modifications

`~/.path` gets sourced along the others (before). It can be used to set the path, without risking it to be overwritten when running the update.


### Custom commands

`~/.extra` gets sourced along the others (after). It can be used to add custom commands, without risking them to be lost when running the update.

Add the same time, it can be used to override aliases, functions, settings, ... from this repository.

## Feedback

Is [welcome](https://github.com/pjan/ubuntu-dotfiles/issues)!

## Credits
 
* [Ethan Schoonover](http://ethanschoonover.com) for his [solarized color scheme](http://ethanschoonover.com/solarized)
