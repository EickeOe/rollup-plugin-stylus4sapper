## Install

```bash
yarn add --dev rollup-plugin-stylus4sapper
```

## usage

```js
import "./test.styl";
```

```js
import { rollup } from "rollup";
import stylus from "rollup-plugin-stylus4sapper";

rollup({
  entry: "main.js",
  plugins: [stylus()]
});
```

文档有时间再优化....
