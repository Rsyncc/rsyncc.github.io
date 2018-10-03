

### 主题特性

- 主题基于 `jekyll 3.8.1` 开发
- 响应式布局
- 文章标签索引
- 文章时间线索引
- 博主个人信息展示
- 支持9种代码高亮主题色
- 支持 `dispus` 、 `来必力` 、 `Gitment` 三种评论系统
- 支持 `百度统计` 、`谷歌分析` 两种网站追踪系统
- 支持13款不同社交平台图标及链接地址指向
- 支持11个不同平台的文章分享路口



### 开始使用



#### 本地部署

​	首先在本地安装 `Jekyll` [详情请戳](https://www.jekyll.com.cn/docs/quickstart/)

​	安装完成之后，使用命令 `jekyll -v` 查看 **jekyll版本号** ，若低于 `jekyll 3.x.x` 则需要升级至 `jekyll 3.x.x` 。 

​	使用 `gem install jekyll-paginate` 或 `sudo gem install jekyll-paginate` 安装Jekyll的分页插件。

​	将源码 `clone` 到本地后，在终端进入 `HardCandy-Jekyll` 根目录，运行 `jekyll server` 或 `bundle exec jekyll serve` ，即可开启jekyll的服务。通过浏览器访问 [http://localhost:4000](http://localhost:4000) ，即可看到本地部署的 `HardCandy-Jekyll` 博客了。

> warning！值得注意的地方：
>
> ​	由于本主题是基于 `jekyll 3.8.1` 开发 ，jekyll的版本差异也许会导致相关显示效果的差异。详情请参考官方文档：[news](https://jekyllrb.com/news/)



### 配置文档

- 开始
  - [关于博客](#关于博客)
  - [写文章](#写文章)
- 组件
  - [博主个人信息](#博主个人信息)
  - [社交媒体](#社交媒体)
  - [首页显示信息](#首页显示信息)
  - [导航栏](#导航栏)
  - [分页](#分页)
  - [代码高亮主题](#代码高亮主题)
  - [友情链接](#友情链接)
  - [页脚](#页脚)
- 第三方服务
  - [评论系统的切换](#评论系统的切换)
  - [文章分享的路口](#文章分享的路口)
  - [网站流量追综的配置](#网站流量追综的配置)



> ​	通用修改 `_config.yml` 文件，你便可以轻松搭建属于你自己的个人博客。
>
> ​	一部分配置，默认已经是配置好的，你只需要修改下面列出的内容即可完成搭建。



#### 关于博客

```yaml
---
# Site settings 配置站点
title: 'your awesome title'
description: 'your web description'
keywords: 'your web keywords, another keywords'
url: 'https://abc.github.io' # your host
---
```

`title` ：用于页面的 title 标签的显示内容

`description` ：网站的简介

`keywords` ：网站的关键词

`url` ：网站域名



#### 写文章

​	博客通过解析 `markdown` 文件来部署文章页面的，所以用户写文章只需要写一篇markdown，并放置在站点根目录下的 `_post` 文件夹即可。具体的markdown语法自行上网搜索学习，或使用markdown编辑器进行写作。推荐一款 markdown编辑器：[typora](https://www.typora.io) 。支持 windows 、mac OSX 、Linux 。
