## :newspaper: vpdate

[![npm version](https://img.shields.io/npm/v/vpdate.svg?version)](https://www.npmjs.com/package/vpdate)

a simple CLI to help keep your package.json version up to date

### demo

![demo gif](docs/demo.gif)

#### install
```sh
npm i -D vpdate
```

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
