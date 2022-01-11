# vue-first-app

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

### Extensions

1. [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

### How to deploy to gitHub

- [Automatically build and deploy a Vue.js app with GitHub Pages](https://blog.logrocket.com/automatically-build-deploy-vuejs-app-github-pages/)
- [execa npm](https://www.npmjs.com/package/execa)
> error while using the above method

```bash
gitpod /workspace/vue-first-app $ npm run deploy-script

> vue-first-app@0.1.0 deploy
> node scripts/gh-pages-deploy.js

/workspace/vue-first-app/scripts/gh-pages-deploy.js:2
const execa = require("execa");
              ^

Error [ERR_REQUIRE_ESM]: require() of ES Module /workspace/vue-first-app/node_modules/execa/index.js from /workspace/vue-first-app/scripts/gh-pages-deploy.js not supported.
Instead change the require of index.js in /workspace/vue-first-app/scripts/gh-pages-deploy.js to a dynamic import() which is available in all CommonJS modules.
    at Object.<anonymous> (/workspace/vue-first-app/scripts/gh-pages-deploy.js:2:15) {
  code: 'ERR_REQUIRE_ESM'
}
```

- [How to deploy a React, Angular and Vue project to Github pages](https://deepinder.me/how-to-deploy-a-react-angular-vue-project-to-github-pages)

- [Deploy Vue.js Application to GitHub Pages - shell script](https://shouts.dev/deploy-vue-app-to-github-pages)
