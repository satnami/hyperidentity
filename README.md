# Hyperidentity

[![NPM Version](https://img.shields.io/npm/v/hyperidentity.svg)](https://www.npmjs.com/package/hyperfeed) [![JavaScript Style Guide](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](http://standardjs.com/)

Store and prove yourself with a [hyperdrive](https://github.com/mafintosh/hyperdrive) archive.

`npm i hyperidentity`

## Synopsis

```js
var hyperidentity = require('hyperidentity')

var me = hyperidentity(drive)

// verify yourself to a service:
// service will give you a challenge for you to response
me.responseChallenge(serviceName, nonce, email, cb)

// save your metadata
me.setMeta(meta, cb)
me.getMeta(cb)

// services will store the data you created on their side in another archive
// link that archive to your identity
me.link(archiveName, key, cb)
```

## License

The MIT License