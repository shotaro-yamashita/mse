mse
===

全文検索エンジン

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/mse.svg)](https://npmjs.org/package/mse)
[![Downloads/week](https://img.shields.io/npm/dw/mse.svg)](https://npmjs.org/package/mse)
[![License](https://img.shields.io/npm/l/mse.svg)](https://github.com/shotaro-yamashita/mse/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g mse
$ mse COMMAND
running command...
$ mse (-v|--version|version)
mse/0.1.0 darwin-x64 node-v10.15.2
$ mse --help [COMMAND]
USAGE
  $ mse COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`mse hello [FILE]`](#mse-hello-file)
* [`mse help [COMMAND]`](#mse-help-command)

## `mse hello [FILE]`

describe the command here

```
USAGE
  $ mse hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ mse hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/shotaro-yamashita/mse/blob/v0.1.0/src/commands/hello.ts)_

## `mse help [COMMAND]`

display help for mse

```
USAGE
  $ mse help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.1.6/src/commands/help.ts)_
<!-- commandsstop -->
