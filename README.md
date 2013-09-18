spritesheet.js
==============

Spritesheet generator in node.js

###Example###
```javascript
var spritesheet = require('spritesheet.js');

spritesheet.generate(['1.png', '2.png'], {name: 'spritesheet'}, function (err) {
  if (err) throw err;

  console.log('Spritesheet successfully generated in', __dirname);
});
```

###Test###
```
mocha test
```
###Supported spritesheet formats###
* Starling / Sparrow


###TODO:###
* command line interface
* file masks
* trimming images
* additional spritesheet formats
  * Easel.js
  * cocos2D