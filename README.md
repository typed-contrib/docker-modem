# Typed docker-modem [![Build Status](https://travis-ci.org/typed-contrib/docker-modem.svg?branch=master)](https://travis-ci.org/typed-contrib/docker-modem)

Type definitions for [docker-modem](https://github.com/apocas/docker-modem).

## Installation

Installation can be done using [typings](https://github.com/typings/typings).

From the registry:
```bash
$ typings install docker-modem --save
```

From the source:
```bash
$ typings install github:typed-contrib/docker-modem --save
```

`docker-modem` module works in `node.js` environment.
So you also have to install `node.js` typings.

```bash
$ typings install env~node --global --save
```

## Contributing

Contributions are welcome !

```bash
# Installation
# Fork this repo (https://github.com/typed-contrib/docker-modem)
# Clone the fork (E.g. `https://github.com/<your_username>/docker-modem.git`)
cd docker-modem

# Install modules and dependencies
npm install

# Test typings over docker-modem samples and tests
npm test
```

Some resources to help writing Typescript type definitions:
 * [Writing Declaration Files](http://www.typescriptlang.org/docs/handbook/writing-declaration-files.html)
 * [typings examples](https://github.com/typings/typings/blob/master/docs/examples.md)

## Tests

This type definitions are tested using source `docker-modem` [tests](https://github.com/apocas/docker-modem/tree/master/test/).

## License

MIT

