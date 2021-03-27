# simple-pie

Super light weight and super simple svg pie diagram

See the demo: https://serjilyashenko.github.io/svg-pie/

## Installation

```shell
npm install simple-pie
```

### Use with ES5 import:
```js
import SVGPie from 'simple-pie';

// will appear soon
```

### Use in NodeJs:
```js
const SVGPie = require('simple-pie');
```

### Use in a browser:
```html
<div id="container"></div>

<script src="node_modules/svg-pie/index.js"></script>
<script>
    const svgElement = new  SVGPie([2, 1, 1, 2]);
    document.getElementById('target-container0').appendChild(svgElement);
</script>
```
