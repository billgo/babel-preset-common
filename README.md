# babel-preset-common
Babel preset based on [@babel/preset-env](https://www.npmjs.com/package/@babel/preset-env)

## How to use

```
  "babel": {
    "presets": [
      ["common", {
        "modules": "commonjs"
      }]
    ],
    "comments": false,
    "minified": true
  },
```

```
["common", {
  "targets": {
    "browsers": ['last 2 versions']
  }
}]
```

```
["common", {
  "targets": {
    "node": "6"
  }
}]
```
