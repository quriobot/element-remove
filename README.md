# element-remove

Just a tiny polyfill for element.remove   

https://developer.mozilla.org/en-US/docs/Web/API/ChildNode/remove  
https://github.com/jserz/js_piece/blob/master/DOM/ChildNode/remove()/remove().md  

[![npm downloads](https://img.shields.io/npm/dm/element-remove.svg?style=flat-square)](https://www.npmjs.com/package/element-remove)


# Usage

```npm install --save element-remove```

# Webpack

Just add element-remove to your entry, you are all good

```['element-remove', 'app.js']```

# Javascript   
You can import this polyfill at your app entry if you are not using webpack

es5
```
require('element-remove');
```
es6
```
import('element-remove');
```

## License

MIT
