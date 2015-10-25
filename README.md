# HCL [![Build Status](http://img.shields.io/travis/fatih/hclfmt.svg?style=flat-square)](https://travis-ci.org/fatih/hclfmt)

hclfmt is a command to format and prettify HCL files. Usually you want to hook
it to your editor. If you use Vim, thers is
[`vim-hclfmt`](https://github.com/fatih/vim-hclfmt) plugin.

## Install

If you have Go installed just do:

```bash
go get github.com/fatih/hclfmt
```

## Usage

The use is similar to `gofmt`. If you pass a file it prints the formatted
output to std output:

```bash
$ hclfmt test.hcl
```

You can pass the `-write` flag to directly overwrite your file:

```bash
$ hclfmt -writ test.hcl
```

Lastly if no arguments are passed, it excepts the input from standard input.


## License

The BSD 3-Clause License - see
[`LICENSE`](https://github.com/fatih/hclfmt/blob/master/LICENSE) for more
details

