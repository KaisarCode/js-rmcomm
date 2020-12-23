# RMComm
[js] Remove comments.

### Install
```
npm install kc-rmcomm
```

### Use
```js
var rmcomm = require('kc-rmcomm');

var str = rmcomm(`
// Comment 1
var a = 1;
/*
Multiline
comment
*/
var b = 2;
`);
console.log(str);
```
