# hpp-middleware-cs5331
an HTTP pollution prevention middleware for express apps

[Node JS](http://nodejs.org) middleware to **protect against HTTP Parameter Pollution attacks**

This is a module for node.js and is installed via npm:

``` bash
npm install hpp-middleware-cs5331 --save
```
## Getting Started

Add the HPP middleware like this:

``` js
// ...
const hpp = require('hpp-middleware-cs533');
const app = express();
app.use(bodyParser.json());
app.use(hpp);
