# parroquia-santa-elena

## Deploy in github pages

```bash
# first generate static project
$ npm run generate:gh-pages

# second deploy whit push-dir
$ npm run deploy
```

## Configuración para GitHub Pages
Agregar las siguientes dependencias push-dir y cross-env:
```
npm install push-dir --save-dev
npm install cross-env --save-dev
```

Agregar los siguientes scripts en package.json
```
"scripts": {
    ...
    "deploy": "push-dir --dir=dist --branch=gh-pages --cleanup",
    "build:gh-pages": "cross-env DEPLOY_ENV=GH_PAGES nuxt build",
    "generate:gh-pages": "cross-env DEPLOY_ENV=GH_PAGES nuxt build && nuxt export"
}
```

Agregar en nuxt.config.js
```
export default {
  ...
  // change on target server value by static
  target: 'statict',
  ...
  router: {
    base: process.env.DEPLOY_ENV === 'GH_PAGES' ? '/tailwind-nuxt-discovery/' : ''
  }
}
```