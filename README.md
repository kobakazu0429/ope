# ope

1Password as [envchain](https://github.com/sorah/envchain)

## Installation

## Latest

```shell
curl -sL https://raw.githubusercontent.com/kobakazu0429/ope/master/ope -o /usr/local/bin/ope
```

## Tagged

```shell
curl -sL https://raw.githubusercontent.com/kobakazu0429/ope/v1.0.0/ope -o /usr/local/bin/ope
```

## Usage

```
$ ope [command] [namespace] [arg...]

Command
  init
    $ ope init
    create ".env" vault

  create
    $ ope create foo ACCESS_KEY ACCESS_TOKEN
    create item and env keys

  list
    $ ope list
    list items

    $ ope list foo
    list envs in namespace

  run
    $ ope run foo python3 main.py
    inject to environment variable

  export
    $ ope export foo
    export envs, NOT MASKING !!
```
