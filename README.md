# babel-preset-common
Babel preset based on [@babel/preset-env](https://www.npmjs.com/package/@babel/preset-env)

## how to use

```
  "babel": {
    "presets": [
      "common", {
        "targets": {
          "modules": false
        }
      }
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
