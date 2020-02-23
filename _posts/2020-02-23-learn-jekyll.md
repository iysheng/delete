---
layout: post
title:  "Learn Jekyll!"
date:   2020-02-23 10:39:30 +0800
categories: jekyll update
---
### learn jekyll with some notes
---
#### jekyll 可以将纯文本转换为静态博客和网页，我在学习通过 jekyll 创建个人博客在 github 上。

##### 1. 基本命令
``` bash
jekyll new PATH # 使用默认的主题在指定的路径创建一个 site
jekyll new PATH --blank # 在指定的路径创建一个空的 site
jekyll build 或者 jekyll b # 构建 site 到默认的 _site 目录
jekyll serve 或者 jekyll s # 源文件改变时，重新构建 site，并且在本地端口可以同步更新
jekyll doctor # 输出任何不推荐的或者是配置的 issue
jekyll clean # 清理动作
jekyll help command # 查看 command 命令的帮助
jekyll new-theme # 创建一个新主题的(scaffold)脚手架
```
    一般情况本地开发时，直接 jekyll s 就可以，当需要发布时，需要 jekyll build。
