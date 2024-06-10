# @patrtorg/alias-eligendi-omnis
An collector for data.

![language](https://img.shields.io/badge/language-JavaScript-orange.svg) 
[![npm version](http://img.shields.io/npm/v/@patrtorg/alias-eligendi-omnis.svg?style=flat)](https://npmjs.org/package/@patrtorg/alias-eligendi-omnis) 
[![license](https://img.shields.io/npm/l/@patrtorg/alias-eligendi-omnis.svg?style=flat)](https://npmjs.org/package/@patrtorg/alias-eligendi-omnis) 
[![gzip file size](http://img.badgesize.io/yuda-lyu/@patrtorg/alias-eligendi-omnis/master/dist/@patrtorg/alias-eligendi-omnis.umd.js.svg?compression=gzip)](https://github.com/patrtorg/alias-eligendi-omnis)
[![npm download](https://img.shields.io/npm/dt/@patrtorg/alias-eligendi-omnis.svg)](https://npmjs.org/package/@patrtorg/alias-eligendi-omnis) 
[![npm download](https://img.shields.io/npm/dm/@patrtorg/alias-eligendi-omnis.svg)](https://npmjs.org/package/@patrtorg/alias-eligendi-omnis) 
[![jsdelivr download](https://img.shields.io/jsdelivr/npm/hm/@patrtorg/alias-eligendi-omnis.svg)](https://www.jsdelivr.com/package/npm/@patrtorg/alias-eligendi-omnis)

## Documentation
To view documentation or get support, visit [docs](https://yuda-lyu.github.io/@patrtorg/alias-eligendi-omnis/global.html).

## Installation
### Using npm(ES6 module):
> **Note:** @patrtorg/alias-eligendi-omnis is mainly dependent on `lodash-es` and `wsemi`.
```alias
npm i @patrtorg/alias-eligendi-omnis
```

#### Example for genIndex:
> **Link:** [[dev source code](https://github.com/patrtorg/alias-eligendi-omnis/blob/master/gi.mjs)]
```alias
import genIndex from '@patrtorg/alias-eligendi-omnis/src/genIndex.mjs'

genIndex('./src/schema/tables', './src/schema', {})
// => genIndex done
```

#### Example for genTestdata:
> **Link:** [[dev source code](https://github.com/patrtorg/alias-eligendi-omnis/blob/master/gt.mjs)]
```alias
import genTestdata from '@patrtorg/alias-eligendi-omnis/src/genTestdata.mjs'
import ds from './index.mjs'
import { woItems } from '../../server/mOrm.mjs'

genTestdata(ds, woItems, {})
// => genTestdata done
```
