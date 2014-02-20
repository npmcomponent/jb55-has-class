*This repository is a mirror of the [component](http://component.io) module [jb55/has-class](http://github.com/jb55/has-class). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/jb55-has-class`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# has-class

  Checks to see if a perticular className exists on an element

  This module exports the equivalent `hasClass` function in jQuery

## Installation

    $ component install jb55/has-class

## API

```js
var hasClass = require('has-class');
var el = document.querySelector('h1');
var hasRed = hasClass(el, "red");
```

## License

  MIT
