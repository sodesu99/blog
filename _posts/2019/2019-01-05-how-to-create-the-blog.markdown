---
layout: "post"
title: "how to create the blog"
date: "2019-01-05 22:23"
---

* Editor： Atom
* OS: MAC OS
* 我在2019年一月建立了这个博客。参考了一些别人写的教程，阮一峰写的阮一峰的网络日志 [搭建一个免费的，无限流量的Blog----github Pages和Jekyll入门 - 阮一峰的网络日志](http://www.ruanyifeng.com/blog/2012/08/blogging_with_jekyll.html)， 为我捋清github pages jekyll 的关系。

* 我想要一个什么样的博客
  1. 干净的，没有多余的东西
  2. 轻松的，不用怎么折腾就可以实现一些基本功能。
  3. 强大的，当我想实现一个需要的功能时有一个清晰的思路去实现。

* 我是如何建立这个博客的
  1. `jekyll new blog` 用jekyll new 一个名为blog的博客
      用这个命令生成的是 gem-based themes site，
      > “With gem-based themes, some of the site’s directories (such as the assets, _layouts, _includes, and _sass directories) are stored in the theme’s gem, hidden from your immediate view.” [https://jekyllrb.com/docs/themes/]
  2. `cd blog` 修改blog文件夹下的_config.yml ,
      选择一个喜欢的theme， 我选择了jekyll-theme-hacker
      [search for jekyll-theme](https://rubygems.org/search?utf8=✓&query=jekyll-theme)
      > theme: jekyll-theme-hacker
      如果想要在本地查看效果需要在Gemfile里面加入
      > gem "jekyll-theme-hacker"
      UK
      > gem "github-pages", group: :jekyll_plugins
  3. 具体设置参考 [https://github.com/pages-themes/hacker]
  4. `bundle install` install the theme
  5. `bundle exec jekyll serve` build the site
  6. 
  7.
