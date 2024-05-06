---
layout: post
title: 使用NEKOBOX生成无限Warp配置，在手机或者电脑上优选最快最适合你的运营商的IP，免费无限流量，无限节点.
date: 2024-05-1 8:18 +0800
last_modified_at: 2024-05-1 8:18 +0800
tags: [VPN/Proxy, WARP]
categories: [网络]
toc:  true
---

> 使用NEKOBOX生成无限Warp配置，在手机或者电脑上优选最快最适合你的运营商的IP，**免费无限流量**，**无限节点**.



## 一 下载所需要的软件

- NekoBoxForAndroid：<a href="https://www.lanzouh.com/iXZMT1q0b65a">下载地址</a>
- Termux-app： <a href="https://www.lanzouh.com/i8toF1q0bexg">下载地址</a>



## 二 安卓 Termux执行代码

>先安装 `wget` ,使用以下命令安装

{% highlight js %}
pkg update && pkg install wget
{% endhighlight %}

>获取 `Warp优选IP` ,主执行代码

{% highlight js %}
wget -N https://gitlab.com/Misaka-blog/warp-script/-/raw/main/files/warp-yxip/warp-yxip.sh && bash warp-yxip.sh
{% endhighlight %}







-----


