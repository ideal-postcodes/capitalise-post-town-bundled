<h1 align="center">
  <img src="http://img.ideal-postcodes.co.uk/Ideal%20Postcodes%20Open%20Source%20Logo@3x.png" alt="Capitalise Post Town Bundled">
</h1>

> JavaScript browser bundles for capitalise-town-town

[![npm version](https://badge.fury.io/js/%40ideal-postcodes%2Fcapitalise-post-town-bundled.svg)](https://badge.fury.io/js/%40ideal-postcodes%2Fcapitalise-post-town-bundled)
[![jscdn](https://badgen.net/jsdelivr/v/npm/@ideal-postcodes/capitalise-post-town-bundled)](https://cdn.jsdelivr.net/npm/@ideal-postcodes/capitalise-post-town-bundled/dist/)
![CI](https://github.com/ideal-postcodes/capitalise-post-town-bundled/workflows/CI/badge.svg)
![Release](https://github.com/ideal-postcodes/capitalise-post-town-bundled/workflows/Release/badge.svg)

This package exports polyfilled, minified copies of `capitalise-post-town` in various formats available on npm and various JavaScript CDNs. It can be readily [dropped in](#usage) on a page.

This package is a transpiled copy of [`capitalise-post-town`](https://github.com/ideal-postcodes/capitalise-post-town-bundled).

## Download

Latest and pinned versions of each bundle can be downloaded from [jsdelivr.com](https://www.jsdelivr.com).

### Latest Versions

- [umd.min.js@latest](https://cdn.jsdelivr.net/npm/@ideal-postcodes/capitalise-post-town-bundled/dist/umd.min.js)
- [esm.min.js@latest](https://cdn.jsdelivr.net/npm/@ideal-postcodes/capitalise-post-town-bundled/dist/esm.min.js)

## Documentation

### Usage

#### UMD

```html
<script src="https://cdn.jsdelivr.net/npm/@ideal-postcodes/capitalise-post-town-bundled/dist/umd.min.js"></script>

<script>
  var capitalisePostTown = IdealPostcodes.capitalisePostTown;
  capitalisePostTown("LONDON"); // => "London"
</script>
```

#### ES Module

```html
<script
  type="module"
  src="https://cdn.jsdelivr.net/npm/@ideal-postcodes/capitalise-post-town-bundled/dist/esm.min.js"></script>

<script type="module">
import { capitalisePostTown } from "https://cdn.jsdelivr.net/npm/@ideal-postcodes/capitalise-post-town-bundled/dist/esm.min.js";
capitalisePostTown("LONDON"); // => "London"
</script>
```

## Licence

MIT
