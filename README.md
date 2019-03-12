## :newspaper: vpdate

[![npm version](https://img.shields.io/npm/v/vpdate.svg)](https://www.npmjs.com/package/vpdate)

a simple CLI to keep your package.json version updated

#### install
```sh
npm i -D vpdate
```


#### demo

![demo gif](docs/demo.gif)

#### use
* add the script
```js
// package.json
// [...]
    "scripts": {
        "push": "vpdate && git push"
    }
// [...]
```

* and have fun

```sh
npm run push
```