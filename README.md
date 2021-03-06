Twitter Intent
===============================================================================

[![Build Status](https://travis-ci.org/rjz/twitter-intent.svg?branch=master)](https://travis-ci.org/rjz/twitter-intent)
[![Coverage Status](https://coveralls.io/repos/github/rjz/twitter-intent/badge.svg?branch=master)](https://coveralls.io/github/rjz/twitter-intent?branch=master)


A utility for building [twitter intents](https://dev.twitter.com/web/intents)

Example
-------------------------------------------------------------------------------

ES5
```js
var twitterIntent = require('twitter-intent');
var href = twitterIntent.tweet.url({
  text: 'Tweet me!',
  hashtags: ['node.js', 'npm']
});

console.log('<a href="' + href + '">Click me!</a>');
```

ES6
```js
import twitterIntent from 'twitter-intent';

const href = twitterIntent.tweet.url({
  text: 'Tweet me!',
  hashtags: ['node.js', 'npm']
});

console.log('<a href="' + href + '">Click me!</a>');
```

Installation
-------------------------------------------------------------------------------

Clone this repository:

    $ npm install twitter-intent

Testing
-------------------------------------------------------------------------------

Lint and run test suite:

    $ npm test

License
-------------------------------------------------------------------------------

MIT

[coveralls]: https://coveralls.io
[gh-pages]: https://pages.github.com
[hoganjs]: http://twitter.github.io/hogan.js
[istanbul]: https://github.com/gotwarlost/istanbul
[jshint]: http://www.jshint.com
[mocha]: https://github.com/visionmedia/mocha
[scrawl]: https://github.com/caolan/scrawl
[travis]: https://travis-ci.org
[nodesecurity]: https://nodesecurity.io/

