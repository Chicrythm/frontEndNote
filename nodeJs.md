nodejs的模块大概可以分为三种：核心模块 第三方模块 自定义模块

## 模块
核心模块：nodejs内置模块，可以理解为nodejs的基础API，例如我们常用的`path os fs`等等。这些模块也是我们nodejs与服务器交互的基础。
第三方模块：nodejs包管理工具平台安装的`npm包`。
自定义模块:这个通常值的是我们自己定义的文件模块。

## 模块的加载编译
文件解析路径：1. 检查是否存在缓存 => 2. 检查是否为核心模块 => 3. 检查扩展名 => 4. 解析执行

## 异步操作
![image.png](https://p9-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/768b684e533540c09585cb8c76fe0f45~tplv-k3u1fbpfcp-zoom-in-crop-mark:3024:0:0:0.awebp?)

## 常用 API
fs：文件的查看，编辑，创建
http: 网络的关键模块
socket：socket网络通信
events：事件模块