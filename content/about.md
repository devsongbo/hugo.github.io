---
title: "About"
date: 2021-05-07T15:35:06+08:00
draft: true
---



假设你需要部署在 GitHub Pages 上，首先在GitHub上创建一个Repository，命名为：coderzh.github.io （coderzh替换为你的github用户名）。

在站点根目录执行 Hugo 命令生成最终页面：

$ hugo --theme=hyde --baseUrl="http://coderzh.github.io/"
（注意，以上命令并不会生成草稿页面，如果未生成任何文章，请去掉文章头部的 draft=true 再重新生成。）

如果一切顺利，所有静态页面都会生成到 public 目录，将pubilc目录里所有文件 push 到刚创建的Repository的 master 分支。

![avatar](https://gitee.com/yadong.zhang/DBlog/raw/master/docs/_media/logo.png)


![avatar](https://gitee.com/yadong.zhang/DBlog/raw/master/docs/_media/logo.png)

