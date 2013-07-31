# ubuntu-dotfiles

## Installation

### Using Git and the bootstrap script

The repository can be cloned wherever you want. The bootstrapper script will pull in the latest version and copy the files to your home folder.

```bash
git clone --recursive https://github.com/pjan/ubuntu-dotfiles.git && cd ubuntu-dotfiles && source bootstrap.sh
```

To update, `cd` into the local `ubuntu-dotfiles` repository and execute:

```bash
source bootstrap.sh
```

The confirmation prompt can be avoided by executing:

```bash
set -- -f; source bootstrap.sh
```

## Feedback

Is [welcome](https://github.com/pjan/ubuntu-dotfiles/issues)!
