Most of the code has been copy-pasted from https://github.com/jshttp/basic-auth

# Why

I use it to protect static html pages.

# Usage

1. Set credentials in index.js
```
const NAME = "super"
const PASS = "secret"
```
2. Build
```
yarn build
```
(or `npm run build` )

3. copy `dist/main.js` to your cloudflare worker and deploy

