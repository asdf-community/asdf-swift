# asdf-swift

Swift plugin for https://github.com/asdf-vm/asdf/

## Requirements

This plugin requires `curl`, `jq` and `tar`. On Ubuntu 22.04 and 24.04, it installs the matching
official Linux toolchain archive. Other distributions use the CentOS 7 toolchain archive.

On Arch Linux you can install the required tools with:

```txt
sudo pacman -S curl jq tar
```

## Installation and Usage

To install this plugin you can run the following command:

```txt
asdf plugin add swift https://github.com/hqnna/asdf-swift
```

Then you can list all available versions of Swift with the following command:

```txt
asdf list all swift
```

To install a specific version of Swift you can run the following command:

```txt
asdf install swift 5.9.1
asdf global swift 5.9.1
```
