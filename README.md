### Hexlet tests and linter status:
[![Actions Status](https://github.com/Kartakinec/frontend-project-46/actions/workflows/hexlet-check.yml/badge.svg)](https://github.com/Kartakinec/frontend-project-46/actions)
[![Maintainability](https://api.codeclimate.com/v1/badges/7f65810d2211cfa5a28e/maintainability)](https://codeclimate.com/github/Kartakinec/frontend-project-46-/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/7f65810d2211cfa5a28e/test_coverage)](https://codeclimate.com/github/Kartakinec/frontend-project-46-/test_coverage)
[![Node CI](https://github.com/Kartakinec/frontend-project-46-/actions/workflows/node.js.yml/badge.svg?event=push)](https://github.com/Kartakinec/frontend-project-46-/actions/workflows/node.js.yml)

## Description

Gendiff is the CLI tool for comparing two different files and show the difference beetween them

## Requirements
Here is minimum requirements for Node.js

| Name | Requirements |
| ------ | ------ |
| Graphics Card | NVIDIA GeForce GTX 960 or compatible AMD |
| Memory | 4 GB |
| CPU | Intel Core 2 Duo E8400 or compatible AMD |
| Free space | 300 mb |
| OS | Windows 7 or Ubuntu 14 |


## Installation
1) `git clone https://github.com/Kartakinec/frontend-project-46-`
2) `make link`

## Usage
 Type that command for help
  ```
  gendiff -h
  ```
 Run command with paths of files to compare

  ```
  gendiff <filepath1> <filepath2>
  ```
 For specify the output format use `-f` or `--format` option. Default format is `stylish`

  ```
  gendiff <filepath1> <filepath2> -f [format]
  ```

## Examples
- **plain objects .json**
https://asciinema.org/a/QKTLEhIAfp9RopJgzYtCo5FVV
- **plain objects in yml and yaml**
https://asciinema.org/a/9YLGGzUPvIxzKGAMJQQlIHs4U
- **plain format**
https://asciinema.org/a/m5JUAIq7jXZTRUHKEACoujzWN
- **stylish format**
https://asciinema.org/a/KxxqH67M3ZEFLVMrsGHUvxhfx
- **json format**
https://asciinema.org/a/0mg4V7SRylv89hjOlH4bPSBUb
