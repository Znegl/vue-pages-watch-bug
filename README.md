# vue-watch-bug

A tiny project to showcase a build bug when using pages in vue.config.js.

Expected behaviour:

Running `ember-cli-service build` and `ember-cli-service build --watch' should create the same file and folder structure in the `dist`folder.

Actual behaviour:

`ember-cli-service build` puts all JS in a sub folder called `dist/js`
`ember-cli-service build --watch` puts all JS directly in the `dist` folder

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

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
