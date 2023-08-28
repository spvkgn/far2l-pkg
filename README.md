[![build status](https://github.com/spvkgn/far2l-termux/actions/workflows/build.yml/badge.svg)](https://github.com/spvkgn/far2l-termux/actions/workflows/build.yml) ![version](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/spvkgn/f53cb6c1d56b0eaf40c88d607fc5fef1/raw/far2l-termux.json)
# [FAR2L](https://github.com/elfmz/far2l) File Manager for Termux

Apt repository with nightly builds

## Installation

```shell
mkdir -p $PREFIX/etc/apt/sources.list.d ; \
echo "deb [trusted=yes] https://spvkgn.github.io/far2l-termux termux extras" | \
tee $PREFIX/etc/apt/sources.list.d/far2l.list >/dev/null && \
apt update && apt install far2l
```
```shell
apt install far2l-plugins-colorer far2l-plugins-netrocks
```
