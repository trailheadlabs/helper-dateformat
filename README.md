> Template helper for adding formatted dates using node-dateformat. Works with Handlebars, Lo-Dash, underscore, or any template engine that supports helper functions. Also compatible with verb, assemble and Template.

A derivative of [node-dateformat](https://github.com/felixge/node-dateformat).

## Run tests

`npm test`

## [Handlebars](https://github.com/wycats/handlebars.js/)

### Register the helper:

    var handlebars = require('handlebars');

    handlebars.registerHelper('dateformat', require('helper-dateformat'));

### Use the helper:

`{{dateformat "MMMM DD, YYYY"}}`

## Original author

**Jon Schlinkert**

+ [github/helpers](https://github.com/helpers)
+ [twitter/helpers](http://twitter.com/helpers)

## License

    Copyright (c) 2014 Jon Schlinkert  
    Released under the MIT license
