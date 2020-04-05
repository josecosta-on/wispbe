wispbe
======

multi commnad utility

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/wispbe.svg)](https://npmjs.org/package/wispbe)
[![Downloads/week](https://img.shields.io/npm/dw/wispbe.svg)](https://npmjs.org/package/wispbe)
[![License](https://img.shields.io/npm/l/wispbe.svg)](https://github.com/josecosta-on/wispbe/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g wispbe
$ wispbe COMMAND
running command...
$ wispbe (-v|--version|version)
wispbe/0.0.1 linux-x64 node-v10.16.3
$ wispbe --help [COMMAND]
USAGE
  $ wispbe COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`wispbe hello [FILE]`](#wispbe-hello-file)
* [`wispbe help [COMMAND]`](#wispbe-help-command)

## `wispbe hello [FILE]`

describe the command here

```
USAGE
  $ wispbe hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ wispbe hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/josecosta-on/wispbe/blob/v0.0.1/src/commands/hello.ts)_

## `wispbe help [COMMAND]`

display help for wispbe

```
USAGE
  $ wispbe help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.2.3/src/commands/help.ts)_
<!-- commandsstop -->
