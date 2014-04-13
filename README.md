# Lōchness

[![Build Status](https://secure.travis-ci.org/robotlolita/lochness.png?branch=master)](https://travis-ci.org/robotlolita/lochness)
[![NPM version](https://badge.fury.io/js/lochness.png)](http://badge.fury.io/js/lochness)
[![Dependencies Status](https://david-dm.org/robotlolita/lochness.png)](https://david-dm.org/robotlolita/lochness)
[![stable](http://hughsk.github.io/stability-badges/dist/stable.svg)](http://github.com/hughsk/stability-badges)


Awesome logging for Node CLI apps.


### Example

```js
var loch = require('lochness')

loch.heading('Lochness')
loch.info('Awesome logging for Node CLI apps.')
loch.warn('Seriously.')
```


### Installing

Just grab it from NPM:

    $ npm install lochness


### Documentation

A quick reference of the API can be built using [Calliope][]:

    $ npm install -g calliope
    $ calliope build


### Tests

You can run all tests using Mocha:

    $ npm test


### Licence

MIT/X11. ie.: do whatever you want.

[Calliope]: https://github.com/robotlolita/calliope
[es5-shim]: https://github.com/kriskowal/es5-shim
