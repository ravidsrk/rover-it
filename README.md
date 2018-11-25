rover-it
========

An Open Source dApp generation tool for Ethereum Smart Contracts

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/rover-it.svg)](https://npmjs.org/package/rover-it)
[![CircleCI](https://circleci.com/gh/ravidsrk/rover-it/tree/master.svg?style=shield)](https://circleci.com/gh/ravidsrk/rover-it/tree/master)
[![Appveyor CI](https://ci.appveyor.com/api/projects/status/github/ravidsrk/rover-it?branch=master&svg=true)](https://ci.appveyor.com/project/ravidsrk/rover-it/branch/master)
[![Codecov](https://codecov.io/gh/ravidsrk/rover-it/branch/master/graph/badge.svg)](https://codecov.io/gh/ravidsrk/rover-it)
[![Downloads/week](https://img.shields.io/npm/dw/rover-it.svg)](https://npmjs.org/package/rover-it)
[![License](https://img.shields.io/npm/l/rover-it.svg)](https://github.com/ravidsrk/rover-it/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g rover-it
$ rover COMMAND
running command...
$ rover (-v|--version|version)
rover-it/0.0.0 darwin-x64 node-v8.12.0
$ rover --help [COMMAND]
USAGE
  $ rover COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`rover hello [FILE]`](#rover-hello-file)
* [`rover help [COMMAND]`](#rover-help-command)

## `rover hello [FILE]`

describe the command here

```
USAGE
  $ rover hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ rover hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/ravidsrk/rover-it/blob/v0.0.0/src/commands/hello.ts)_

## `rover help [COMMAND]`

display help for rover

```
USAGE
  $ rover help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.1.4/src/commands/help.ts)_
<!-- commandsstop -->
