# Git

## Installation

You will need [Homebrew](http://brew.sh) to install `git`.

```
$ brew update
$ brew install git
```

## SSH Key

To use Git, you need an SSH key. You will also use the SSH key for other tools like `ssh` (duh), `scp` or `rsync`. A few things about SSH Keys.

 - There are two parts: the public key and the private key.
 - It is safe to share the public key. You will share it with Github for instance.
 - Keep the private key private.
 - The private key will be protected with a passphrase.
 - Never forget your passphrase. There's no way to recover it.
 - For the love of Maple, never forget your passphrase.

To generate your passphrase, follow these instructions: https://help.github.com/articles/generating-ssh-keys/

## Updating Git

```
$ brew update
$ brew upgrade git
```
