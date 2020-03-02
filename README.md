# tiny
The tiniest npm module


## Install
```
$ npm install @jcstang/tiny
```

## Usage
```
const tiny = require("jcstang/tiny");

tiny("so much space!");
//=> "somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
// at tiny (<anonymous>:2:41)
// at <anonymous>:1:1
```