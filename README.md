# Hexo迁移

换电脑不烦恼

## 安装Node.js

* [下载地址](https://nodejs.org/en/download/)

## 安装Git

* [下载地址](https://git-scm.com/download/)
* [安装教程](http://jingyan.baidu.com/article/90895e0fb3495f64ed6b0b50.html)
* [Pro Git（中文版）](http://git.oschina.net/progit/)
* [常用命令](http://blog.csdn.net/u011974987/article/details/50973740)


## Clone项目

* 将项目Clone到本地
* 如果有拷贝.ssh，将.ssh中的内容放到用户.ssh文件夹
* 如果没有拷贝.ssh，将GitHub账户的老公钥删除，在本地创建新ssh key，将公钥放到GitHub的新公钥认证中

## 配置Hexo环境

* Git Bash，输入安装hexo的命令`npm install -g hexo-cli`
* 执行`hexo init e:\blog`命令完成hexo的初始化，`cd e:\blog`
* 接着把项目中的文件覆盖到`e:\blog`中去
* `npm install`，系统会可以根据package.json文件中dependencies的配置安装所有依赖包

------

接下来可以开开心心地使用hexo啦！