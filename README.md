# Modified rolldate

1. Open /dist/rolldate.js
2. Edit css
3. Minify https://javascript-minifier.com/
4. Paste rolldate.min.js
5. ???
6. Profit

## Usage
### es6
```js
import Rolldate from 'rolldate'
new Rolldate({
  el:'#date'
})
```
### commonJS
```js
var Rolldate = require('rolldate');
new Rolldate({
  el:'#date'
})
```
### amd
```js
require(['rolldate'],function(Rolldate){
  new Rolldate({
    el:'#date'
  })
})
```
### cmd
```js
seajs.use('rolldate',function(undefined){
    new Rolldate({
      el:'#date'
    })
});
```

Original by weijhfly (https://www.npmjs.com/package/rolldate)