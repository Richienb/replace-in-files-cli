# replace-in-files-cli [![Build Status](https://travis-ci.com/sindresorhus/replace-in-files-cli.svg?branch=master)](https://travis-ci.com/sindresorhus/replace-in-files-cli)

> Replace matching strings and regexes in files


## Install

```
$ npm install --global replace-in-files-cli
```


## Usage

```
$ replace-in-files --help

  Usage
    $ replace-in-files <files…>

  Options
    --regex           Regex pattern to find  (Can be set multiple times)
    --string          String to find  (Can be set multiple times)
    --replacement     Replacement string  (Required)
    --ignore-case     Search case-insensitively

  Examples
    $ replace-in-files --string='horse' --regex='unicorn|rainbow' --replacement='🦄' foo.md
    $ replace-in-files --regex='v\d+\.\d+\.\d+' --replacement=v$npm_package_version foo.css

  You can use the same replacement patterns as with `String#replace()`, like `$&`.
```
