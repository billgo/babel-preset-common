# babel-preset-common

Babel preset based on [@babel/preset-env](https://www.npmjs.com/package/@babel/preset-env)

## for Node.js project

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

## for React.js project

```
  "babel": {
    "presets": [
      "common"
    ],
    "comments": false,
    "minified": true
  }
```