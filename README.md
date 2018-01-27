# 使用說明

➜  myFirstWebpack git:(master) npm start

> webpackProject@1.0.0 start
> webpack-dev-server

Project is running at http://localhost:8080/


***
# webpack.config.js
``` js 
const path = require('path')

module.exports = {
  entry: ['./app/index.js'],
  output: {
    path: path.resolve(__dirname, 'build'),
    filename: 'bundle.js'
  }
}
```

