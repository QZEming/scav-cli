# scav-cli
用于从github上拉取模板到本地的脚手架工具  
可在初始化时配置vuex，UI框架，css预处理语言  
使用
```
npm i scav-cli -g
```
来下载到全局

使用
```
scav init
```
或者
```
scav i
```
来初始化项目

使用scav avxf来添加vuex相关的模板文件到store文件夹下的modules文件夹下

# 版本更新
## 2.1.2
增加了vue-router的配置

## 2.1.1
增加了advx指令，用于添加vuex模板文件

## 2.1.0
增加对App.vue的ejs模板处理  
增加对UI框架的配置  
增加对css预处理语言的配置  

## 2.0.0
增加了ejs的模板渲染，修改index.html，package.json等文件的相关内容  
增加了是否启用vuex的选择  
增加了模板文件，在启用vuex的时候将模板文件写入  

## 1.1.0
修改了生成后的package.json相关内容  
增加对版本的提问  
在模板下载后自动执行npm i将依赖包下载到node_modules中

## 1.0.0
实现基本功能