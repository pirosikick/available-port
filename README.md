# available-port
Search available port number in Node.js

## Usage

```javascript
var availablePort = require('available-port');

availablePort.searchCountUp(3000, function (err, no) {
  ...
});

availablePort.searchCountDown(3000, function (err, no) {
  ...
});
```

## License

MIT
