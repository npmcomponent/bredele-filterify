*This repository is a mirror of the [component](http://component.io) module [bredele/filterify](http://github.com/bredele/filterify). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/bredele-filterify`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# filterify

  Turns any function into an array filter

## Installation

  Install with [component(1)](http://component.io):

    $ component install bredele/filterify

## Usage

```js
var filterify = require('filterify');
var pair = filterify(function(n){return !(n % 2);});

pair([1,2,3]);
// [2]

```

## License

  MIT
