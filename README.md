# wechat

itchat是一个开源的微信个人号接口，使用python调用微信从未如此简单。

使用不到三十行的代码，你就可以完成一个能够处理所有信息的微信机器人。

当然，该api的使用远不止一个机器人，更多的功能等着你来发现，比如这些。

该接口与公众号接口itchatmp共享类似的操作方式，学习一次掌握两个工具。

如今微信已经成为了个人社交的很大一部分，希望这个项目能够帮助你扩展你的个人的微信号、方便自己的生活。

#安装
可以通过本命令安装itchat：

pip install itchat
#简单入门实例
有了itchat，如果你想要给文件传输助手发一条信息，只需要这样：

import itchat

itchat.auto_login()

itchat.send('Hello, filehelper', toUserName='filehelper')

#说明
本项目演示获取微信号好友的男女比例和生成好友签名的词云

#import
需要另外安装
>1.qrcode

>2.pypng

#参考
http://itchat.readthedocs.io/zh/latest/

![demo](signature.png)