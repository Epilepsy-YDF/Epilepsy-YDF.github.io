---
layout: post
title: 怎么用 GitHub Pages 创建网站
category: tutorials
tags: [GitHub, Pages, Website]
---

最简单方便的免费建站方法。

## 创建 GitHub 账户
* [GitHub 主页](https://github.com)不解释。    
P.S.:记住自己的用户名，有用。    

## 创建一个仓库
1. 点击 GitHub 首页右上角加号，点击 New repository。    
2. 把仓库的名字改成"*用户名*.github.io"。    

## 添加网页文件
1. 在你想要的位置打开 Git Bash    
2. 键入`git clone https://github.com/用户名/用户名.github.io.git`    
3. 键入`cd 用户名.github.io`    
4. 在`*用户名*.github.io`文件夹里面放上你的网页文件。    
5. 键入`git add --all`    
6. 键入`git commit -m "Initial commit"`    

## 将本地网页文件上传至 GitHub
* 键入`git push -u origin master`    

## 完成
* 至此建站过程全部完成，访问`*用户名*.github.io`看看效果吧:D    

> 详见 [GitHub Pages](https://pages.github.com)
