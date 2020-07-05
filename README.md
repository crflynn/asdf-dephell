# asdf-dephell

[![githubactions](https://github.com/crflynn/asdf-dephell/workflows/build/badge.svg)](https://github.com/crflynn/asdf-dephell/actions)

[dephell](https://github.com/dephell/dephell) python project management plugin for [asdf](https://github.com/asdf-vm/asdf) version manager

## Requirements

* [python3](https://www.python.org/downloads/) and [virtualenv](https://pypi.org/project/virtualenv/)

```bash
brew install asdf
```

The installation relies on some version of `python3` already installed with the `virtualenv` package.

## Install

With [asdf](https://asdf-vm.com/) already installed:

```
asdf plugin-add dephell https://github.com/crflynn/asdf-dephell.git
```

## Use

To list all versions

```bash
asdf list-all dephell
```

To install a specific version of dephell

```bash
asdf install dephell 0.8.3
```

To uninstall a specific version of dephell

```bash
asdf uninstall dephell 0.8.3
```

To set a project-specific version of dephell

```bash
asdf local dephell 0.8.3
```