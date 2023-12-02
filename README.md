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

### [tailwindcss](https://tailwindcss.com/docs/guides/vite#vue)

* install
```
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```
tailwind.config.js
```js
// /** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{vue,js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```
style.css
```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```
### [.sass, .less, .stylus](https://vitejs.dev/guide/features.html#css)

* install
```
# .scss and .sass
npm add -D sass

# .less
npm add -D less

# .styl and .stylus
npm add -D stylus
```