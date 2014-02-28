*This repository is a mirror of the [component](http://component.io) module [yields/placeholder](http://github.com/yields/placeholder). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/yields-placeholder`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# placeholder

  Placeholder for older browsers.

  tested on
    - ie7
    - ie8
    - ie9

## Installation

    $ component install yields/placeholder

## Example

It adds `.placeholder` class when the placeholder is active, it is styled
with a color of `#a8a8a8` by default.

```js
var placeholder = require('placeholder')
  , textarea = document.getElementsByTagName('textarea')[0]
  , input = document.getElementsByTagName('input')[0];

placeholder(textarea).set('textarea');
placeholder(input).set('input');
```

## License

  MIT
