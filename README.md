# Vite

 ### Click documentation [Vite](https://vitejs.dev/)

 ## Install
* npm 
```
 npm create vite@latest
```
* yarn
```
$ yarn create vite
```
* install
```
 npm instal
```

 ## Plugins

  ### [vite-plugin-inspect](https://github.com/antfu/vite-plugin-inspect)

* install
```
npm i -D vite-plugin-inspect
```
Add plugin to your vite.config.ts:

```ts
// vite.config.js
import Inspect from 'vite-plugin-inspect'

export default {
  plugins: [
    Inspect()
  ],
}
```
Then run `npm run dev` and visit [localhost:5173/__inspect/](http://localhost:5173/__inspect/) to inspect the modules.