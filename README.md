# babel-preset-common
Babel preset based on [@babel/preset-env](https://www.npmjs.com/package/@babel/preset-env)

## How to use

```
  "babel": {
    "presets": [
      [
        "common",
        {
          "modules": "commonjs"
        }
      ]
    ],
    "comments": false,
    "minified": true
  }
```

```
  "babel": {
    "presets": [
      [
        "common",
        {
          "targets": ['last 2 versions']
        }
      ]
    ]
  }
```

```
  "babel": {
    "presets": [
      [
        "common",
        {
          "targets": {
            "node": "6"
          }
        }
      ]
    ]
  }
```
