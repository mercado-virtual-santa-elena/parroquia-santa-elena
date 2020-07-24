# Parroquia Santa Elena

## Instrucciones para realizar despliegue en Github pages

```bash
# first generate static project
$ npm run generate:gh-pages

# second deploy whit push-dir
$ npm run deploy
```

## Configuración para GitHub Pages
* Agregar las dependencias **push-dir** y **cross-env**:
```javascript
npm install push-dir --save-dev
npm install cross-env --save-dev
```

* Agregar los siguientes scripts en **package.json**
```javascript
"scripts": {
    // previous code ...

    "deploy": "push-dir --dir=dist --branch=gh-pages --cleanup",
    "build:gh-pages": "cross-env DEPLOY_ENV=GH_PAGES nuxt build",
    "generate:gh-pages": "cross-env DEPLOY_ENV=GH_PAGES nuxt build && nuxt export"
}
```

* Agregar en **nuxt.config.js**
```javascript
export default {
  // previous code ...

  // change on target server value by static
  target: 'statict',

  // more code ...

  router: {
    base: process.env.DEPLOY_ENV === 'GH_PAGES' ? '/parroquia-santa-elena/' : ''
  }
}
```