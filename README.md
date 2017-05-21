# d3-data-visualizations
This is data visualizations using D3.js.
## D3: Data-Driven Documents
D3 (or D3.js) is a JavaScript library for visualizing data using web standards. D3 helps you bring data to life using SVG, Canvas and HTML. D3 combines powerful visualization and interaction techniques with a data-driven approach to DOM manipulation, giving you the full capabilities of modern browsers and the freedom to design the right visual interface for your data.
## Installing
If you use npm, `npm install d3`. Otherwise, download the [latest release](https://github.com/d3/d3/releases/tag/v4.9.1). The released bundle supports anonymous AMD, CommonJS, and vanilla environments. You can load directly from [d3js.org](https://d3js.org/), [CDNJS](https://cdnjs.com/libraries/d3), or [unpkg](https://unpkg.com/d3@4.9.1/). For example:

`<script src="https://d3js.org/d3.v4.js"></script>`

For the minified version:

`<script src="https://d3js.org/d3.v4.min.js"></script>`

You can also use the standalone D3 microlibraries. For example, [d3-selection](https://github.com/d3/d3-selection):

`<script src="https://d3js.org/d3-selection.v1.js"></script>`

D3 is written using [ES2015 modules](http://2ality.com/2014/09/es6-modules-final.html). Create a [custom bundle using Rollup](https://bl.ocks.org/mbostock/bb09af4c39c79cffcde4), Webpack, or your preferred bundler. To import D3 into an ES2015 application, either import specific symbols from specific D3 modules:

`import {scaleLinear} from "d3-scale";`

Or import everything into a namespace (here, `d3`):

`import * as d3 from "d3";`

In Node:

`var d3 = require("d3");`

You can also require individual modules and combine them into a `d3` object using [Object.assign](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/assign):

`var d3 = Object.assign({}, require("d3-format"), require("d3-geo"), require("d3-geo-projection"));`
