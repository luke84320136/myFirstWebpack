# 使用說明
➜  myFirstWebpack git:(master) npm start

> webpackProject@1.0.0 start /Users/LukeLan/myFirstWebpack
> webpack-dev-server

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

