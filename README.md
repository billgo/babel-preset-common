# babel-preset-common
Babel preset based on [@babel/preset-env](https://www.npmjs.com/package/@babel/preset-env)

```
  "babel": {
    "presets": [
      [
        "common",
        {
          "modules": "commonjs",
          "targets": {
            "node": "6.16"
          }
        }
      ]
    ],
    "comments": false,
    "minified": true
  }
```