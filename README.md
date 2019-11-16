# Babel-tool
#### 安装npm-node.js

见我blog [csdn_Mr.J](https://blog.csdn.net/Ms_yjk/article/details/103034826 "Babel-tool安装及使用")  
 
#### 安装babel插件
`npm install -g babel-cli --svae-dev`

#### 安装babel 插件
`npm install --save-dev babel-preset-env`
<br> other one:<br>
`npm install --save-dev babel-cli babel-preset-es2015`
#### 增加scripts 脚本
在<strong>package.json</strong>添加(更改)：<br>
```
"scripts": {
    "babel": "babel test.js --watch --out-file finalCode.js"
  }
  
  "babel":{
    "presets":["es2015"]
  }
```
#### 测试运行
`npm run babel`
