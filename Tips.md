各种Tip
=======
接下来介绍下在Linux系统装完之后，要掌握的基本概念，常用命令及操作
---------
##root
root是Linux下最高权限的用户，类似Windows下的管理员administer。
###切换到root

    su
然后输入密码即可切换到root用户
>注意
>>在Linux系统刚被装上之后，有时候默认情况下root账户是被锁定的，即使你`su`，并且敲了正确密码，也会提示密码错误。
>>>此时键入`sudo passwd`然后根据提示再重新键入几次密码，root用户的权限就解锁了。该命令也可用于修改root密码。

###退出root
最快捷的方式就是按组合键 Ctrl+D

##Bash相关
###上下键
通过上下键可以翻阅历史命令。而无需重新键入相同命令。
###Tab键
在一个命令未输完的时候，按两下Tab键会出现命令补全提示。
###Alt+.
`Alt`和`.`组合键可快速调用上一个命令的参数。
不过如果上一个命令有多个参数，则只能调用最后一个参数。
###Ctrl相关
|组合键|描述|
|------|-----
|Ctrl+Z|暂停当前程序，丢入后台运行
|Ctrl+C|终止当前程序
|Ctrl+D|退出当前用户的终端登录
|Ctrl+R|搜索历史命令
>上述为Ubuntu终端的组合键，其他系统还支持Ctrl+S和Ctrl+Q

##授人以渔
高手是善于寻找帮助的人
###man
如果你对某个命令的用法不熟悉，可以使用`man`命令来查看。如

    man ls
可以查看`ls`命令的用法。
###info
man是Unix系统的产物，而Linux也提供了自己的解决方案 <kbd>info</kbd>。
info中带星号的行，按回车可以跳进新的页面，按shift+u返回。
>原先info要优秀与man，但近代以来差异已经不大。info逐渐没落，极少更新。
建议使用man

###tldp.org
The Linux Document Project
一个Howto网站。
###doc 
查看 `/usr/share/doc/`
###百度谷歌
    内事不决问百度，外事不决问谷歌
如果找不到中文资料，那么要去谷歌找英文资料，谷歌比百度要强大丰富的多。
不过需要搜索英文。

