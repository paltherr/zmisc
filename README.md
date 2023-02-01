# zmisc: Miscellaneous Zsh Utilities

Miscellaneous Zsh utilities that haven't (yet) been judged worthy
and/or stable enough to be promoted to their own package. New random
utilities may be added anytime. Existing ones may eventually be moved
to their own package.

## Installation

### Homebrew

```sh
brew install paltherr/zsh/zmisc
```

### Manual

```sh
cd /usr/local/opt
git clone https://github.com/paltherr/zmisc.git
cd /usr/local/bin
ln -s ../opt/zmisc/src/bin/zmisc.zsh
ln -s ../opt/zmisc/src/bin/show-args
cd /usr/local/share/zsh/site-functions
ln -s ../../../opt/zmisc/src/functions/show-args
```

## Shell Commands

- `show-args`

    Prints the number of arguments provided and their values.

## Zsh Functions

- `show-args`

    Prints the number of arguments provided and their values.
