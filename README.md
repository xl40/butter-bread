##### 编码过程中遇见的问题和搜索的答案

###### yarn
类似 npm 的工具
https://yarn.bootcss.com/docs/usage/
```
初始化一个新项目   yarn init
安装项目的全部依赖  yarn
将依赖项添加到不同依赖项类别中 yarn add nodemon --dev

```

###### package.json 的文件结构

http://nodejs.cn/learn/the-package-json-guide

```
version 表明了当前的版本。
name 设置了应用程序/软件包的名称。
description 是应用程序/软件包的简短描述。
main 设置了应用程序的入口点。
private 如果设置为 true，则可以防止应用程序/软件包被意外地发布到 npm。
scripts 定义了一组可以运行的 node 脚本。
dependencies 设置了作为依赖安装的 npm 软件包的列表。
devDependencies 设置了作为开发依赖安装的 npm 软件包的列表。
engines 设置了此软件包/应用程序在哪个版本的 Node.js 上运行。
browserslist 用于告知要支持哪些浏览器（及其版本）。
```

