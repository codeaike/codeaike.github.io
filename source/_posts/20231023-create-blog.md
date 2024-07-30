---
title: 手把手教你搭建自己的个人博客
tag: "随笔"
date: 2023-10-23
---

10分钟即可拥有属于程序员的浪漫——搭建自己的个人博客。

今天我们来聊一聊如何使用 Hexo 和 GitHub Pages 搭建带评论功能的极简博客。

## 概述
个人博客地址：[https://codeaike.github.io/](https://codeaike.github.io/)

项目地址：[https://github.com/codeaike/codeaike.github.io](https://github.com/codeaike/codeaike.github.io)

效果图如下：
![博客效果图](/img/blog-show.png)

先简单介绍下需要用到的几个组件：
### 什么是 Hexo
Hexo是一款基于Node.js的静态博客框架，快速、简洁且高效，支持Markdown，支持自定义主题和插件，支持在GitHub Pages上部署。

### 什么是 GitHub Pages
GitHub Pages支持在GitHub上直接部署我们的博客网站项目。域名采用GitHub Pages的域名，如：https://username.github.io/

### 什么是 Giscus
Giscus是一个基于 GitHub Discussions 的评论系统。安装此App到自己的GitHub，并对自己的项目开启此功能即可使用。

### 什么是 AirCloud
AirCloud是Hexo的一个极简风格的主题，集成了Giscus的评论功能，让博客可以轻松集成基于GitHub登录的评论系统。

## 以下是具体操作步骤
**第一步**：在 GitHub 上创建一个Public仓库，如：username.github.io<sup>[1]</sup>。

**第二步**：初始化一个Hexo项目<sup>[2]</sup>。
```
npm install hexo-cli -g
hexo init blog
cd blog
npm install
hexo server
```
如果没有安装Git和Node，参考[Hexo安装文档](https://hexo.io/zh-cn/docs/)。

**第三步**：在 GitHub Pages 上部署 Hexo<sup>[3]</sup>。点击GitHub项目的Actions，可以看到完成Workflows是否成功。访问 https://username.github.io，验证是否部署成功。

**第四步**：引入AirCloud主题<sup>[4]</sup>。

在[https://hexo.io/themes/](https://hexo.io/themes/)主题商店里面发现了AirCloud主题，极简风格，还能自动集成评论系统，迫不及待改成这个主题。

在项目的themes目录下导入[https://github.com/aircloud/hexo-theme-aircloud](https://github.com/aircloud/hexo-theme-aircloud),文件夹需要命名为`aircloud`，否则会报错。仿照[https://github.com/aircloud/hexo-aircloud-blog)](https://github.com/aircloud/hexo-aircloud-blog)完成各项配置即可。

**第五步**：在 Hexo 主题中配置评论系统，参考[https://github.com/aircloud/hexo-theme-aircloud](https://github.com/aircloud/hexo-theme-aircloud)的Readme操作即可。

## 如果你需要换个域名
GitHub Pages 提供了相应的方案，不过这个貌似就得买国外域名了，因为指向的GitHub。

如果你在使用阿里云等国内云厂商的服务器，那么这套代码完全可以部署到自己的服务器上，然后买域名，申请备案就好了，这样当然就不是免费啦。服务器、域名等费用肯定需要自己承担了。

## 后续如果发布博客文章
超级简单，Hexo支持markdown，新写一篇md格式的文档放到项目source/_posts目录下就好了，具体可参考Hexo官方文档。

有问题或者想要改进的地方也欢迎在评论区留言。

心动的朋友赶快行动起来吧！

### 参考链接
- [1] [GitHub Pages 快速入门](https://docs.github.com/zh/pages/quickstart)
- [2] [Hexo](https://hexo.io/zh-cn/)
- [3] [在 GitHub Pages 上部署 Hexo](https://hexo.io/zh-cn/docs/github-pages)
- [4] [AirCloud 主题](https://github.com/aircloud/hexo-theme-aircloud)
- [4] [AirCloud Demo](https://github.com/aircloud/hexo-aircloud-blog)
- [4] [hexo本地测试运行重启后页面空白,提示 : WARN No layout: index.html](https://www.zhihu.com/question/38781463)
- [5] [Giscus 评论](https://giscus.app/zh-CN)
- [6] [Markdown 语法](https://markdown.com.cn/basic-syntax/)
