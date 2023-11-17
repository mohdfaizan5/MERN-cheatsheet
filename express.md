# Express.js

Express js is a routing for node js. It makes things more simple for node.


Basic boilerplate
```js
const express = require('express')
const app = express()

app.get("/", (request, response)=>{
  response.send('Server is running')
})

app.listen(3000)
```


### POST


### Middleware


### Serving Static files



### Auth


### Routing other
