# mocha-watch

better watch for mocha.

Automatically detects all dependencies of your tests and reruns them on change.

### Install

```sh
npm install -g mocha-watch
```

### Usage

```sh
mocha-watch # drop-in replacement for mocha
```

### Exclude a required file from watching

```coffee
after(() =>
  delete require.cache["full/path/to/file"]
)

## License
Copyright (c) 2017 Paul Pflugradt
Licensed under the MIT license.
