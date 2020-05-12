# vue-cli4 + vue2.6 + vuex + vue-router + axios + element-ui

> 项目功能说明:

 1. 采用了vue-cli搭建
 2. 使用了vue-router来实现路由，实现单页面应用
 3. 使用vuex做状态管理工具
 4. axios做请求工具
 5. element-ui做ui框架。
 6. 项目实现了动态路由，跨域配置，请求拦截，路由拦截，状态本地存储等。
 7. 项目加入了`px2rem,lib-flexible`实现的移动端适配方案
 8. 线上地址[访问](https://jackzhujie.github.io/vue-study)
```
 /*当前目录命令行输入下面的命令*/
    npm config set registry https://registry.npm.taobao.org/
    /* -g安装到全局  -s安装到dependencies（需要打包之后还要使用的）节点，-d安装到devDependencies（只需要在开发时用到的）  */
    npm isntall cnpm -g
    /*用cnpm安装依赖*/
    cnpm install
    /* 项目启动 */
    npm run serve
    /* 打包 */
    npm run build
```
`node-sass`能容易安装失败，可以参照(这个)[https://segmentfault.com/a/1190000010984731] 来安装。
