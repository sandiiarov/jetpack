# deploy-to-netlify

```js
{
  "scripts": {
    "start": "jetpack",
    "build": "jetpack build",
    "serve": "serve dist",
    "deploy": "jetpack build && cp _redirects dist && netlifyctl deploy"
  }
}
```
