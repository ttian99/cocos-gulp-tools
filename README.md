# cocos-gulp-tools 工具

## 使用
```js
// 打包zip
var cgt = require('cocos-gulp-tools');
cgt.zip('../../build/web-mobile', '../../build/game', 'game', function() {
    console.log('zip over！');
});
```

## 目前可用的功能
### - 1.cgt.compile 命令行打包
### - 2.cgt.imagemin 压缩图片资源
### - 3.cgt.htmlmin 合并html和初始js、css的功能
### - 4.cgt.uglify 压缩js文件
### - 5.cgt.zip 打包zip

