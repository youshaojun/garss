# Github Actions Rss (garss, 嘎RSS! 已收集{{rss_num}}个RSS源, 生成时间: {{ga_rss_datetime}})

信息茧房是指人们关注的信息领域会习惯性地被自己的兴趣所引导，从而将自己的生活桎梏于像蚕茧一般的「茧房」中的现象。

## 《嘎!RSS》🐣为打破信息茧房而生

![](./_media/ga-rss.png)

这个名为**嘎!RSS**的项目会利用免费的Github Actions服务, 提供一个内容全面的信息流, 让现代人的知识体系更广泛, 减弱信息茧房对现代人的影响, 让**非茧房信息流**造福人类~
[《嘎!RSS》永久开源页面: https://github.com/zhaoolee/garss](https://github.com/zhaoolee/garss)

## 推荐使用什么软件订阅RSS？
我推荐一款免费的浏览器扩展程序Feedbro ，使用教程[Chrome插件英雄榜第96期《Feedbro》在Chrome中订阅RSS信息流](https://www.v2fy.com/p/096-feedbro-2021-02-27/)

## 主要功能
1. 收集RSS, 打造无广告内容优质的 **头版头条** 超赞新闻页
2. 利用Github Actions, 搜集全部RSS的头版头条新闻标题和超链接, 并自动更新到首页,当天最新发布的文章会出现🌈 标志

邮件内容区开始>
<h2>新蒸熟{{new_num}}个小蛋糕🍰(文章) 生产时间 {{ga_rss_datetime}} 保质期24小时</h2>

{{news}}

<邮件内容区结束

## 已收集RSS列表

| 编号 | 名称 | 描述 | RSS  |  最新内容 |
| --- | --- | --- | --- |  --- |
| <h2 id="软件工具">软件工具</h2> |  |   |  |
| <div id="S001" style="text-align: center;"><img src="./_media/favicon/S001.png" width="30px" style="width:30px;height: auto;"/><br><span>S001</span></div> |  不死鸟 | 不死鸟:专注分享优质资源 | {{latest_content}} |  [订阅地址](https://iao.su/feed) | 
| <div id="S002" style="text-align: center;"><img src="./_media/favicon/S002.png" width="30px" style="width:30px;height: auto;"/><br><span>S002</span></div> | 精品MAC应用分享 | 精品MAC应用分享，每天分享大量mac软件，为您提供优质的mac软件,免费软件下载服务 |  {{latest_content}} | [订阅地址](https://xclient.info/feed) | 
| <div id="S003" style="text-align: center;"><img src="./_media/favicon/S003.png" width="30px" style="width:30px;height: auto;"/><br><span>S003</span></div> | 老殁 | 免费推荐优秀软件 |  {{latest_content}} | [订阅地址](https://www.mpyit.com/feed) |
| <div id="S004" style="text-align: center;"><img src="./_media/favicon/S004.png" width="30px" style="width:30px;height: auto;"/><br><span>S004</span></div> | 鹏少资源网 | 专注于精品软件收录分享 |   {{latest_content}} | [订阅地址](https://www.jokerps.com/feed) |
| <div id="S005" style="text-align: center;"><img src="./_media/favicon/S005.png" width="30px" style="width:30px;height: auto;"/><br><span>S005</span></div> | 小众软件 | 分享免费、小巧、实用、有趣、绿色的软件 | {{latest_content}} | [订阅地址](https://www.appinn.com/feed/) | 
| <div id="S006" style="text-align: center;"><img src="./_media/favicon/S006.png" width="30px" style="width:30px;height: auto;"/><br><span>S006</span></div> | 懒得勤快的博客 | 懒得勤快，互联网分享精神，勤于发现，乐于分享 |  {{latest_content}} | [订阅地址](https://masuit.com/rss) |
| <div id="S007" style="text-align: center;"><img src="./_media/favicon/S007.png" width="30px" style="width:30px;height: auto;"/><br><span>S007</span></div> | 反斗限免 | 反斗软件旗下软件限免资讯网站 |  {{latest_content}} | [订阅地址](https://free.apprcn.com/feed/) | 
| S008 | 异次元软件世界  | 极具人气和特色的软件网站！专注于推荐优秀软件、APP应用和互联网资源，每篇图文评测都极其用心，并提供大量软件资源下载。 | {{latest_content}}  |  [订阅地址](https://rsshub.v2fy.com/iplay/home) |  
| <h2 id="活着的个人独立博客">活着的个人独立博客</h2> |  |   |  |
| <div id="B001" style="text-align: center;"><img src="./_media/favicon/B001.png" width="30px" style="width:30px;height: auto;"/><br><span>B001</span></div> |  阮一峰的网络日志 | 一个科技博客，讲解的知识通俗易懂 |  {{latest_content}} | [订阅地址](http://www.ruanyifeng.com/blog/atom.xml) |
| <div id="B002" style="text-align: center;"><img src="./_media/favicon/B002.png" width="30px" style="width:30px;height: auto;"/><br><span>B002</span></div> | 当我在扯淡 | 王垠的博客，观点奇妙有趣 |  {{latest_content}} | [订阅地址](https://yinwang1.wordpress.com/feed/) |

## 批量导入所有RSS订阅

OPML V2.0:  [https://raw.githubusercontent.com/zhaoolee/garss/main/zhaoolee_github_garss_subscription_list_v2.opml](https://raw.githubusercontent.com/zhaoolee/garss/main/zhaoolee_github_garss_subscription_list_v2.opml) 

OPML V2.0 备用CDN地址: [https://cdn.jsdelivr.net/gh/zhaoolee/garss/zhaoolee_github_garss_subscription_list_v2.opml](https://cdn.jsdelivr.net/gh/zhaoolee/garss/zhaoolee_github_garss_subscription_list_v2.opml)



> 如果RSS软件版本较老无法识别以上订阅,请使用[V1.0版本的OPML订阅信息](https://raw.githubusercontent.com/zhaoolee/garss/main/zhaoolee_github_garss_subscription_list_v1.opml) [V1.0版本的OPML订阅信息备用CDN地址](https://cdn.jsdelivr.net/gh/zhaoolee/garss/zhaoolee_github_garss_subscription_list_v1.opml)


## 如何定制自己的私人简报?

从 github.com/zhaoolee/garss.git 仓库, fork一份程序到自己的仓库

允许运行actions

![允许运行actions](https://cdn.fangyuanxiaozhan.com/assets/1630216112533FANcC1QY.jpeg)

在EditREADME.md中, 展示了zhaoolee已收集的RSS列表, 你可以参考每行的格式, 按行增删自己订阅的RSS

然后按照下图设置发件邮箱相关内容即可!

![](https://cdn.fangyuanxiaozhan.com/assets/1629970189283arACkBKe.png)

在根目录, tasks.json中配置收件人, 收件人是一个对象数组, 数组中的邮箱, 都会收到邮件, 后续会扩展更多功能~

```
{
    "tasks": [
        {
            "email": "zhaoolee@gmail.com"
        },
        {
            "email": "zhaoolee@foxmail.com"
        }
    ]
}
```

设置完成后 在README.md文件的底部加个空格，并push，即可触发更新！

## 无法收到邮件怎么办

可以按照以下代码，自测一下自己的HOST, PASSWORD，USER 是否能顺利发邮件

```
!pip install yagmail

import yagmail

# 连接邮箱服务器
yag = yagmail.SMTP(user="填USER参数", password="填PASSWORD参数", host='填HOST参数')

# 邮箱正文
contents = ['今天是周末,我要学习, 学习使我快乐;', '<a href="https://www.python.org/">python官网的超链接</a>']

# 发送邮件
yag.send('填收件人邮箱', '主题:学习使我快乐', contents)
```

在线自测地址 [Colab： https://colab.research.google.com/](https://colab.research.google.com/)

![在线自测](https://i.v2ex.co/zQWM0V6b.png)

## 发送邮件的效果

![手机端优化后的邮件效果](https://cdn.fangyuanxiaozhan.com/assets/163039979740967wCT8RQ.jpeg)

![PC端优化后的邮件效果](https://cdn.fangyuanxiaozhan.com/assets/1630399693988c2tk8n7k.png)

