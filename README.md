# babel-preset-es2015-amd

> Babel preset for all es2015 plugins using amd instead of commonjs.

## Install

```sh
$ npm install --save-dev babel-preset-es2015-amd
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["es2015-amd"]
}
```

### Via CLI

```sh
$ babel script.js --presets es2015-amd 
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  presets: ["es2015-amd"]
});
```
