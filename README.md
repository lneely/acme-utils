# acme

This is a collection of configuration files and scripts that I find
useful for my daily workflow in acme
([plan9port](https://github.com/9fans/plan9port) version, this is not
tested in [edwood](https://github.com/rjkroege/edwood)).

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
$HOME. Updates are manual.

## Usage

`rc` supports executing commands in `bin/` subdirectories using the
format `subdir/cmd`. For example: to find a function definition from
inside a golang repository, the command from inside of acme is
`go/fndef`. To increase or decrease the indentation of a selection,
pipe the selection through `a/i+` and `a/i-` respectively.

## Thanks

- [@9fans](https://github.com/9fans) and [rsc](https://github.com/rsc) for [plan9port](https://github.com/9fans/plan9port)
- [@mkmik](https://github.com/mkmik) for
https://github.com/mkmik/awesome-acme
- [@sminez](https://github.com/sminez) for
https://github.com/sminez/acme-corp
- [@mpl](https://github.com/mpl) for https://github.com/mpl/xplor

