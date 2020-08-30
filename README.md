![nsh logo](./logo.svg)

nsh
===

Unix shell powered by JavaScript

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/@0x77/nsh.svg)](https://npmjs.org/package/nsh)
[![Codecov](https://codecov.io/gh/0x77dev/nsh/branch/master/graph/badge.svg)](https://codecov.io/gh/0x77dev/nsh)
[![Downloads/week](https://img.shields.io/npm/dw/@0x77/nsh.svg)](https://npmjs.org/package/nsh)
[![License](https://img.shields.io/npm/l/@0x77/nsh.svg)](https://github.com/0x77dev/nsh/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g nsh
$ nsh COMMAND
running command...
$ nsh (-v|--version|version)
nsh/0.0.0 darwin-x64 node-v14.7.0
$ nsh --help [COMMAND]
USAGE
  $ nsh COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`nsh hello [FILE]`](#nsh-hello-file)
* [`nsh help [COMMAND]`](#nsh-help-command)

## `nsh hello [FILE]`

describe the command here

```
USAGE
  $ nsh hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ nsh hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/0x77dev/nsh/blob/v0.0.0/src/commands/hello.ts)_

## `nsh help [COMMAND]`

display help for nsh

```
USAGE
  $ nsh help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.0/src/commands/help.ts)_
<!-- commandsstop -->

---
Special thanks to [https://bashlogo.com/](https://bashlogo.com/) and [https://prospectone.io/](https://prospectone.io/) for creating bash logo, we took it as a base for our logo.
