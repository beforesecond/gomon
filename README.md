# Gomon

`gomon` forks from codegangsta/gin,acoshift and remove unused features.

Just run `gomon` in your app directory.
`gomon` will automatically recompile your code when it
detects a change.

## Installation

```shell
go get -u github.com/beforesecond/gomon
```

## Basic usage

```shell
gomon main.go
```

Options

```txt
   --bin value, -b value         name of generated binary file (default: ".goreload")
   --path value, -t value        Path to watch files from (default: ".")
   --build value, -d value       Path to build files from (defaults to same value as --path)
   --excludeDir value, -x value  Relative directories to exclude
   --all                         reloads whenever any file changes, as opposed to reloading only on .go file change
   --buildArgs value             Additional go build arguments
   --logPrefix value             Setup custom log prefix
   --help, -h                    show help
   --version, -v                 print the version
```
