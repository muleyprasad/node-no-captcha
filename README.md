node-no-captcha
==================
  Express middleware for User's response verification in [https://developers.google.com/recaptcha](Google no-captcha Recaptcha)
  
## Example:

```js
var express = require('express'),
  recaptcha = require('node-no-captcha'),
  secret = 'your_secret_key';
  
  app.post('/login', recaptcha.verify(secret), function(..));
```

## Installation

```
$ npm install node-no-captcha
```