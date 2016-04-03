# Hello Webpack


**无配置文件**

```
webpack ./entry.js bundle.js --module-bind 'css=style!css'
```

**有配置文件**

webpack指令会在当前目录下加载配置文件`webpack.config.js`

```
webpack
```

**带进度条**

```
webpack --progress --colors
```

**查看模式**

如果任何文件发生变化，会触发重新编译

```
webpack --progress --colors --watch
```

**开发服务器**

开发服务器使用webpack的查看模式

```
npm install webpack-dev-server -g
webpack-dev-server --progress --colors
```

访问如下网址，当页面重新重新编译以后，会自动刷新加载

http://localhost:8080/webpack-dev-server/bundle/

如果仅访问 http://localhost:8080/ 则需要手动刷新






参考
http://webpack.github.io/docs/tutorials/getting-started/
