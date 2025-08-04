---
title: astro部署教程(主题fuwari)
published: 2025-08-04
tags: [教程, astro, fuwari]
category: 教程
draft: true
---
# 检查
```vb
npm -version
```
如果报错请先安装npm

# 初始化fuwari
在你想创建blog的文件夹中运行终端输入下面的命令
```vb
npm create fuwari@latest
```
一路回车即可
安装依赖
```vb
npm install
```
测试
```vb
npm run dev
```
# github配置
创建一个GitHub仓库，名字自取，运行下面的命令
```vb
git init
git add .
git commit -m "first commit" //引号里面填写你对此次上传文件的描述
git branch -M main
git remote add origin https://github.com/你的github用户名/仓库名.git
git push -u origin main
```
# netlify部署
[netlify](https://app.netlify.com/)
选择你上传的github仓库