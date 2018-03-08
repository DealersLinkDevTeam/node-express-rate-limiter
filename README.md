# node-express-rate-limiter

`node-express-rate-limit` is a cache-based, request reate limiter for use with [`expressJS`](https://www.npmjs.com/package/express). It is designed for use with [`request-utils`](https://www.npmjs.com/package/@dealerslink/node-express-request-utils) but can be used without. It caches a store of IP address, Method, and Request tuples used to make any request and then temporarily blocks requests from those sources once a limit for those requests have been exceeded.

# [Installation](#installation)
<a name="installation"></a>

```shell
npm install @dealerslink/express-rate-limiter
```

# [Usage](#usage)
<a name="usage"></a>

```js
const RateLimiter = require('@dealerslink/node-express-rate-limiter');
rateLimiter = new RateLimiter('rateLimit');
```

See wiki for more details.
