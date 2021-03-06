# BulletPush [![Build Status](https://travis-ci.org/markus1189/bullet-push.png?branch=master)](https://travis-ci.org/markus1189/bullet-push) [![License](https://img.shields.io/github/license/markus1189/bullet-push.svg)](https://img.shields.io/github/license/markus1189/bullet-push.svg)

## Intro ##

BulletPush is a simple client for
[Pushbullet](https://www.pushbullet.com/) written in Haskell.

## Install ##

You can install it via `cabal install`.

In addition to the executable, you need your Pushbullet token.
Provide it either as a file `~/.bulletpush` with your token as the
sole content or the `--token` argument.  You can get a token on your
[Account Settings](https://www.pushbullet.com/account) page.

## Examples ##

```
bullet-push note "My first note" "Hello World"
bullet-push -e "email address" link "bullet-push rocks" "https://github.com/markus1189/bullet-push"
bullet-push list todo "todo item 1" "todo item 2"
```

## Help ##

For a description of comandline arguments and commands, see:
```
$ bullet-push --help
```
