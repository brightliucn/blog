---
layout: post
title:  "Windows上安装jekyll"
date:   2018-06-29 22:08:16 +0800
categories: jekyll
---
## 在Windows上安装Ruby环境 ##

在地址<https://rubyinstaller.org/downloads/>下载ruby安装包，选择带有**Devkit**的安装包,因为jekyll中部分代码需要使用编译系统进行编译。
![]({{ site.url }}/imgs/jekyll-install/download_page.jpg)

## 安装ruby ##
Next到底,选择默认的路径,勾选**Add Ruby executables to your PATH**把ruby加入到系统环境中，勾选**MSYS2 development toolchain**安装开发工具链。

![]({{ site.url }}/imgs/jekyll-install/setup1.jpg)

![]({{ site.url }}/imgs/jekyll-install/setup2.jpg)

![]({{ site.url }}/imgs/jekyll-install/setup3.jpg)

![]({{ site.url }}/imgs/jekyll-install/setup4.jpg)

![]({{ site.url }}/imgs/jekyll-install/setup5.jpg)


## 安装jekyll ##
安装完ruby之后，启动ruby命令行，执行下面的命令安装jekyll。
``` ruby
	gem install jekyll
```
查看jekyll版本
```
	jekyll -v
```
现在，jekyll已经安装成功了，你可以使用jekyll创建自己的blog了。