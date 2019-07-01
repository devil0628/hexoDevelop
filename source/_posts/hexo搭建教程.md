----
title: Hexo实战
----
# Hexo博客搭建教程
## 安装环境
* 安装node.js,git 以及cnpm
* 安装全局hexo-cli:npm install -g hexo-cli
* 验证 hexo -v
---

## 正式搭建
 * hexo init  初始化;
 * hexo s(start)  启动hexo;
---
## 新建一篇文章
 * souce下的——posts下hexo n(new) "My first blog";
 * vim 进入该目录，也可以自己用markdown编辑器;
---
## 推送至github
 * 新建一个仓库 new respository，命名***.github.io
 * 在刚才本地目录下安装：npm install --save hexo-deployer-git
 * 设置里面 _config.xml文件，里面的deploy:type:git,repo:github的库地址，branch:分支，修改完成之后保存
 * 部署 hexo d(deploy)

 ## 自定义主题 yilia
 * git clone https://github.com/litten/hexo-theme-yilia.git  至themes/yilia 
 * 配置_config_xml,修改里面theme:yilia
 * hexo d(deploy)

