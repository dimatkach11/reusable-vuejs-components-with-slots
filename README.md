# reusable-vuejs-components-with-slots

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

# Reusable Vue.js Components with Slots

Why we need slots?

If we want to add an inline SVG icon component to our button via the props. We can't pass components via the props, but we can pass HTML or components via slots.

[using slots](https://vueschool.io/lessons/using-slots)

## Named Slots

Slots can have names. 

```html
<template v-slot:header>Header</template>
OR
<template #header>Header</template>
```

[named-slots](https://vueschool.io/lessons/named-slots)