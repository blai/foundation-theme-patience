# foundation-theme-patience
> foundation-theme-patience theme. Generated using [generator-foundation](https://github.com/blai/generator-foundation). Works greate with [fashionista](https://github.com/blai/fashionista)

This is a demo theme for the following tools:
* [generator-foundation](https://github.com/blai/generator-foundation)
* [fashionista](https://github.com/blai/fashionista)

Theme color from: [http://www.studiopress.com/palettes/patience](http://www.studiopress.com/palettes/patience)
Font from: [http://www.dafont.com/janda-stylish-script.font](http://www.dafont.com/janda-stylish-script.font)

### play with it
1. clone it and `cd foundation-theme-patience`
2. `npm install`
3. `grunt`

### use it with your express.js app
1. Add the following to your express.js script
```javascript
var app = require('express')();
var fashionista = require('fashionista');
fashionista([require('foundation-theme-patience')]).decorate(app);
...
```

2. Add the following to your html `<head>`
```html
<script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>
    <script type="text/javascript" src="/fashionista"></script>
```

3. run `npm install foundation-theme-patience fashionista --save` from your project root

# License
[WTFPL](http://www.wtfpl.net/about/)
