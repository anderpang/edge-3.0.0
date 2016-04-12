# edge-3.0.0
javascript, css, compress, yuicompress-2.4.6, gzip, merge file

## 自创自用前端利器
###  增加Gzip功能
#### 环境：
Java+Nodejs+window系统（未测其他系统）
####功能：
1、css编写，不用写前缀，保存后自动加-webkit-、-moz-、-o-前缀，并压缩文件，增加Gzip功能，文件合并。

现支持的、不加前缀的css属性有：transform、transition、animation、@keyframes、user-select、linear-gradient、radial-gradient。

2、js保存后自动压缩。

3、源码中创建文件夹、保存文件，压缩路径中自动生成。

4、配置简单。

### src/js/otherpath/merge.json
[
  ["../jquery-1.8.0.js","a.js","bbb.js"],
  ["a.js","bbb.js"]
]
