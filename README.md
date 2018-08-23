# vue-toast-c

> 基于vue开发的弹窗提示插件。

## API
* mes: [ String ] : 弹窗内容
* timeout: [ Number, default: 2000 ] : 弹窗持续时间
* callback: [ Function ] : 弹窗结束回调函数

## NPM
``` bash
npm install vue-toast-c --save
```

## main调用示例
``` bash
import Toast from 'vue-toast-c'
Vue.use(Toast);
```

## 组件中调用示例
``` bash
this.$toast({mes: 'Hello World!'});
```

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```

For detailed explanation on how things work, consult the [docs for vue-loader](http://vuejs.github.io/vue-loader).
