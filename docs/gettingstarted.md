# Getting Started

## Quick setup
Setup `slix` for the current user in a few simple steps:
``` sh
curl https://slix-tools.de/releases/slix-bootstrap-pkg-latest.tar.zst -o slix-bootstrap-pkg.tar.zst
tar -xaf slix-bootstrap-pkg.tar.zst && rm slix-bootstrap-pkg.tar.zst
source slix-bootstrap-pkg/activate
```

By default, slix will not be available. To enable it you need to run `source slix-bootstrap-pkg/activate` for each shell.
To permanently activate it add `source slix-bootstrap-pkg/activate` to your `.bashrc`.

## Temporary environment

In this example we want to run a clean environment with only bash (provides bash) and coreutils (provides ls, mkdir, touch etc.).
The slix command will download the newest package list and synchronize the packages
```
slix -Sy bash coreutils
```

To run an environment just call:
```
slix run bash coreutils
```
