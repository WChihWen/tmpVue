# real-world-vue

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```
### fixed Component name “xxx“ should always be multi-word vue/multi-word-component-names

```
vue.config.js

const { defineConfig } = require('@vue/cli-service')
module.exports = defineConfig({
  transpileDependencies: true,
  lintOnSave: false
})

```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
