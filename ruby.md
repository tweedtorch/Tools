# Ruby

The key problem with Ruby is that you may have to deal with different incompatible versions. The best tool to manage them is `rbenv`.

## Prerequisite

This requires that [git](./git.md) is already installed.

## Install

To install, use the "Basic GitHub Checkout": https://github.com/rbenv/rbenv#basic-github-checkout

Additionally, you need the ability to add Ruby versions. This uses the `ruby-build` plugin for `rbenv`. See instructions for [installing an rbenv plugin](https://github.com/rbenv/ruby-build#installing-as-an-rbenv-plugin-recommended)


## Use

See: https://github.com/rbenv/ruby-build#usage

## Update

To update rbenv:

```
$ cd ~/.rbenv
$ git pull
```

To install new versions of ruby that were not available when you installed `ruby-build`, you will need to update the `ruby-build` plugin:

```
$ cd ~/.rbenv/plugins/ruby-build
$ git pull
```


