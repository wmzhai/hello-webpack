# Hello-Webpack

# webpack

没有配置文件时：

```
webpack ./entry.js bundle.js --module-bind 'css=style!css'
open index.html
```

有配置文件`webpack.config.js`时，webpack指令会在当前目录下加载它

```
webpack
open index.html
```


参考
http://webpack.github.io/docs/tutorials/getting-started/
