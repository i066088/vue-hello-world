



```
$ npm install vue
vue create hello-world

```

https://cli.vuejs.org/guide/creating-a-project.html#vue-create

https://vuejs.org/v2/guide/installation.html









https://www.runoob.com/vue3/vue3-install.html

```
# 全局安装 vue-cli
$ cnpm install -g @vue/cli
# 安装完后查看版本
$ vue --version
@vue/cli 4.5.11
```



```
$ cnpm i -g @vue/cli-init
```



D:\work\2021\vue\my-app\vue.config.js

```javascript
module.exports = {
  // options...
  publicPath:'./'
}
```

https://code.visualstudio.com/docs/nodejs/vuejs-tutorial



https://cli.vuejs.org/config/#target-browsers



## vue.config.js

`vue.config.js` is an optional config file that will be automatically loaded by `@vue/cli-service` if it's present in your project root (next to `package.json`). You can also use the `vue` field in `package.json`, but do note in that case you will be limited to JSON-compatible values only.

The file should export an object containing options:

```js
// vue.config.js

/**
 * @type {import('@vue/cli-service').ProjectOptions}
 */
module.exports = {
  // options...
}
```

### [#](https://cli.vuejs.org/config/#baseurl)baseUrl