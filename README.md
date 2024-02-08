# acme

This is a collection of configuration files and scripts that I find
useful for my daily workflow in acme.

- **a/** contains commands for acme itself
- **g/** contains commands for working with git
- **go/** contains commands for working with golang files and projects
- **lib/** contains my plumbing rules

## Setup

**Method 1**. Create symlinks in $HOME pointing to this
repository. Pull updates automatically using `git pull` from within
the repository. For example:

```
ln -s $HOME/src/github.com/lneely/acme/acme $HOME/bin/acme
ln -s $HOME/src/github.com/lneely/acme/a $HOME/bin/a
ln -s $HOME/src/github.com/lneely/acme/g $HOME/bin/g
ln -s $HOME/src/github.com/lneely/acme/go $HOME/bin/go
ln -s $HOME/src/github.com/lneely/acme/lib $HOME/lib
```

**Method 2**. Copy the files and directories from this repository to
$HOME/bin. Updates are manual.

## Thanks

- [@mkmik](https://github.com/mkmik) for
https://github.com/mkmik/awesome-acme
- [@sminez](https://github.com/sminez) for
https://github.com/sminez/acme-corp
- [@mpl](https://github.com/mpl) for https://github.com/mpl/xplor

