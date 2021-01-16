# Code Snippet for a responsive Bootstrap-Vue Card deck

FooComponent.vue works as a component for Vue or Nuxt having installed <a href="https://bootstrap-vue.org/" target="_blank"><b>Bootstrap-Vue</b></a> (BV).


You can install BV:

[//]: <> With npm
npm install vue bootstrap bootstrap-vue

[//]: <> With yarn
yarn add vue bootstrap bootstrap-vue

Make sure to add it as a dependency in <i>nuxt.config.js</i>.


```js[nuxt.config.js]
//...
 export default {
    modules: [
        'bootstrap-vue/nuxt',
        '@nuxtjs/axios',
        '@nuxtjs/auth',
        // '@nuxtjs/toast',
        // Docs: https: //github.com/richardeschloss/nuxt-socket-io
        'nuxt-socket-io'
    ],
//...
}```
