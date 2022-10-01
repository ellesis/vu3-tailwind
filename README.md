# vue3-tailwind

vue create my-awesome-app
cd my-awesome-app

npm install -D tailwindcss postcss autoprefixer
or
npm install -D tailwindcss@latest postcss@latest autoprefixer@latest

npx tailwindcss init -p

mkdir src/styles && touch src/styles/app.css

https://javascript.plainenglish.io/how-to-setup-tailwind-css-in-vue-3-405c889842d9
https://tailwindcss.com/docs/guides/vite

# library

## font awesome

```bash
npm i --save @fortawesome/fontawesome-svg-core

# Free icons styles
npm i --save @fortawesome/free-solid-svg-icons
npm i --save @fortawesome/free-regular-svg-icons
npm i --save @fortawesome/free-brands-svg-icons

# for Vue 3.x
npm i --save @fortawesome/vue-fontawesome@latest-3
```

https://fontawesome.com/docs/web/use-with/vue/

# vue project setup and start

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

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).
