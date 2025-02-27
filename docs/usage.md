# Usage

<!-- This is generated by scripts/generate-usage.sh. Don't edit this file directly. -->

```console
$ aqua help
NAME:
   aqua - Version Manager of CLI. https://github.com/suzuki-shunsuke/aqua

USAGE:
   aqua [global options] command [command options] [arguments...]

VERSION:
   0.7.8 (91ac6d29f77ecadc960e04c1b3b6cff704141fff)

COMMANDS:
   install, i   Install tools
   exec         Execute tool
   list         List packages in Registries
   which        Output the file path of the given command
   generate, g  Search packages in registries and output the configuration interactively
   version      Show version
   help, h      Shows a list of commands or help for one command

GLOBAL OPTIONS:
   --log-level value         log level [$AQUA_LOG_LEVEL]
   --config value, -c value  configuration file path [$AQUA_CONFIG]
   --help, -h                show help (default: false)
   --version, -v             print the version (default: false)
```

## aqua install

```console
$ aqua help install
NAME:
   aqua install - Install tools

USAGE:
   aqua install [command options] [arguments...]

OPTIONS:
   --only-link, -l  create links but skip download packages (default: false)
   --test           test file.src after installing the package (default: false)
   --all, -a        install all aqua configuration packages (default: false)
   
```

## aqua exec

```console
$ aqua help exec
NAME:
   aqua exec - Execute tool

USAGE:
   aqua exec [arguments...]
```

## aqua generate

```console
$ aqua help generate
NAME:
   aqua generate - Search packages in registries and output the configuration interactively

USAGE:
   aqua generate [command options] [arguments...]

OPTIONS:
   -f value  the file path of packages list.
   
```

## aqua list

```console
$ aqua help list
NAME:
   aqua list - List packages in Registries

USAGE:
   aqua list [arguments...]
```
