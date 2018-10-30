---
layout: post
title:  "阿里云日志查询警告配置"
description: 配置阿里云日志分析警告 
categories: configuration
author: Helen
---
1. 配置查询
例如，要全文搜索 "aa bb"，并且tag指定为 _path_: /home/log.log
那么就需要这样搜索：
"aa bb" and __tag__: _path_: /home/log.log
如下图。
图片最上方是查询间隔，为了展示效果，这里选择了“一周”，真正应用的时候，选择“1分钟”即可
![]({{site.baseurl}}/images/2018103001.png)


点右上角的“另存为告警”，进入告警配置

![]({{site.baseurl}}/images/2018103002.png)
![]({{site.baseurl}}/images/2018103003.png)

配置完成后，返回日志库

可以看到刚才配置的告警已经保存成了快速查询分析，在“快速查询分析” 菜单可以看到
![]({{site.baseurl}}/images/2018103004.png)

在“告警配置”可以看到告警记录
![]({{site.baseurl}}/images/2018103005.png)