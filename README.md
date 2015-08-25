# changes

> Keep track of your code releases.

Uses [Git](http://git-scm.com) tags and [SemVer](http://semver.org) to manage your project's changelog file.

## Install

Since `changes` is just a binary, you can move it to your `/usr/bin` and it'll be globally available.

## Usage

```sh
$ changes --help

Usage: changes [PATH] [OPTIONS]

  Keep track of your code releases.
  Uses Git tags and SemVer to manage your project's changelog file.

Example:
  changes .

Options:
  -v --version             Display software version
  -h --help                Display software usage
  -t --template            Custom header template for changelog entries
  -d --date                Custom date for changelog entries
  -f --force               Force a fresh changelog file creation

```

## License

MIT © [Rafael Rinaldi](http://rinaldi.io)
