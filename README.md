# resolve ipfs

![Travis](https://img.shields.io/travis/alincode/resolve-ipfs.svg)
[![codecov](https://codecov.io/gh/alincode/resolve-ipfs/branch/master/graph/badge.svg)](https://codecov.io/gh/alincode/resolve-ipfs)![npm downloads](https://img.shields.io/npm/dt/resolve-ipfs.svg)
[![Dependency Status](https://img.shields.io/david/alincode/resolve-ipfs.svg?style=flat)](https://david-dm.org/alincode/resolve-ipfs)

### Install

```sh
npm install resolve-ipfs
```

### Usage

* parser

```js
const resolve = require('resolve-ipfs');
const path = 'http://raw.githubusercontent.com/OpenZeppelin/openzeppelin-solidity/master/contracts/math/SafeMath.sol';
let content = await resolve.parser(path);
```

## License
MIT © [alincode](https://github.com/alincode/resolve-ipfs)