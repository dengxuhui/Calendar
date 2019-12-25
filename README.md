# calendar

> Calendar and todolist can add

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).


# Vscode调试配置
```
{
    "version": "0.2.0",
    "configurations": [
      {
        "type": "chrome",
        "request": "launch",
        "name": "vuejs: chrome",
        "url": "http://localhost:8080",
        "webRoot": "${workspaceFolder}/src",
        "breakOnLoad": true,
        "sourceMapPathOverrides": {
          "webpack:///src/*": "${webRoot}/*"
        }
      }
    ]
  }
```