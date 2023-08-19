# Slix - User-space package manager

**Warnung**: Currently, in a very early stage, not ready for real usage.

A user-space package manager. The main focus is to create reproducible environments with small of space overhead.


Some tools which can be used to achieve similar goals:

- [conda](https://docs.conda.io/en/latest/) - A user-space package manager. Allows mulitple environments.
- [Homebrew](https://brew.sh/index_de) - A user-space package manager.
- [pip](https://pypi.org/project/pip/) with [python venv](https://docs.python.org/3/library/venv.html) - Environments for tools installable via pip.
- [nix](https://nixos.org) - A package-manager. Allows to create multiple environments. Highly reproducible. Multiuser support.
- containers like [docker](https://www.docker.com/) or [buildah](https://buildah.io/) - Usable with different package distributions, isolation of filesystem, network stack and much more.
- [divenv](https://direnv.net/) - Per directory environment variables
