<p align="center">
    <img src="https://user-images.githubusercontent.com/6702424/80216211-00ef5280-863e-11ea-81de-59f3a3d4b8e4.png">  
</p>
<p align="center">
    <i></i>
    <br>
    <br>
    <img src="https://github.com/garronej/json-antlr-tools-ts/workflows/ci/badge.svg?branch=main">
    <img src="https://img.shields.io/bundlephobia/minzip/json-antlr-tools-ts">
    <img src="https://img.shields.io/npm/dw/json-antlr-tools-ts">
    <img src="https://img.shields.io/npm/l/json-antlr-tools-ts">
</p>
<p align="center">
  <a href="https://github.com/NicoLaval/json-antlr-tools-ts">Home</a>
  -
  <a href="https://github.com/NicoLaval/json-antlr-tools-ts">Documentation</a>
</p>

# Install / Import

```bash
$ npm install --save json-antlr-tools-ts
```

```typescript
import { myFunction, myObject } from "json-antlr-tools-ts";
```

Specific imports:

```typescript
import { myFunction } from "json-antlr-tools-ts/myFunction";
import { myObject } from "json-antlr-tools-ts/myObject";
```

## Import from HTML, with CDN

Import it via a bundle that creates a global ( wider browser support ):

```html
<script src="//unpkg.com/json-antlr-tools-ts/bundle.min.js"></script>
<script>
  const { myFunction, myObject } = vtl_2_0_antlr_tools_ts;
</script>
```

Or import it as an ES module:

```html
<script type="module">
  import {
    myFunction,
    myObject,
  } from "//unpkg.com/json-antlr-tools-ts/zz_esm/index.js";
</script>
```

_You can specify the version you wish to import:_ [unpkg.com](https://unpkg.com)

## Contribute

```bash
npm install
npm run build
npm test
```
