# Archived project. No maintenance. 

This project is not maintained anymore and is archived. Feel free to fork and
make your own changes if needed. For more detail read my blog post: [Taking an indefinite sabbatical from my projects](https://arslan.io/2018/10/09/taking-an-indefinite-sabbatical-from-my-projects/)

Thanks to everyone for their valuable feedback and contributions.


# hclfmt [![Build Status](http://img.shields.io/travis/fatih/hclfmt.svg?style=flat-square)](https://travis-ci.org/fatih/hclfmt)

hclfmt is a command to format and prettify HCL files. It's similar to the
popular `gofmt` command. Hook it with your favourite editor or use it from the
command line.

## Install

If you have Go installed just do:

```bash
go get github.com/fatih/hclfmt
```

## Editor integration

* [vim-hclfmt plugin](https://github.com/fatih/vim-hclfmt)
* [atom-hclfmt](https://atom.io/packages/hclfmt)

## Usage

The usage is similar to `gofmt`. If you pass a file it prints the formatted
output to std output:

```bash
$ hclfmt config.hcl
```

You can pass the `-w` flag to directly overwrite your file:

```bash
$ hclfmt -w config.hcl
```

If no arguments are passed, it excepts the input from standard input.


## License

The BSD 3-Clause License - see
[`LICENSE`](https://github.com/fatih/hclfmt/blob/master/LICENSE) for more
details

