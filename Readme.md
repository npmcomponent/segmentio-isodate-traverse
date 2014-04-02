*This repository is a mirror of the [component](http://component.io) module [segmentio/isodate-traverse](http://github.com/segmentio/isodate-traverse). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/segmentio-isodate-traverse`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# isodate-traverse

  Traverse an object (or array) and convert all ISO strings into Dates.

## Installation

    $ component install segmentio/isodate-traverse

## Example

```js
var traverse = require('isodate-traverse');

var obj = {
  date: '2013-09-04T00:57:26.434Z'
};

var traversed = traverse(obj);
// {
//   date: [object Date]
// }
```

## API

### traverse(obj, [strict])
  Traverse an `obj`, converting all ISO strings to real Dates. By default, `strict` mode will be enabled, requiring at least YYYY-MM-DD

## License

  MIT
