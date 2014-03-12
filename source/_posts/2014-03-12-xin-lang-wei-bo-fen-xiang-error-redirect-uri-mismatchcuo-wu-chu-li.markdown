---
layout: post
title: "新浪微博分享error:redirect_uri_mismatch错误处理"
date: 2014-03-12 21:22:40 +0800
comments: true
categories: 
---
做微博分享功能时候出现`redirect_uri_mismatch`错误，需要在微博开放平台上设置安全域名和授权回调页网址.

1.设置安全域名
默认设置成`whalecloud.com`
{% img /images/2014-03-12-1.png %}

2.设置授权回调页网址
默认设置成`http://sns.vhalecloud.com/sina2/callback`
{% img /images/2014-03-12-2.png %}

3.设置测试账户(未通过审核的应用只有测试账户才能使用分享功能)
{% img /images/2014-03-12-3.png %}
