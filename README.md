# perlan/node-webapp

Docker Image for an example web app in Node.js

```javascript
var express = require('express');

// Constants
var PORT = 8080;

// App
var app = express();
app.get('/', function (req, res) {
  res.send('Node.js server is running.\n');
});

app.listen(PORT)
console.log('Running on http://localhost:' + PORT);
```
