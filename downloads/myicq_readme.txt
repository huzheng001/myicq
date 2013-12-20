gaim-myicq使用说明。

1.下载
http://cosoft.org.cn/project/showfiles.php?group_id=4585
http://forlinux.yeah.net

2.安装
用rpm包安装：
rpm -Uvh gaim-0.61-myicq.i386.rpm
用源码包安装:
tar -xjvf gaim-myicq-0.6.0.tar.bz2
cd gaim-myicq-0.6.0
./configure
make
make install

3.运行
安装完后可以在终端里输入
gaim &
就可以运行了。
在gnome菜单里也可以找到gaim的图标，点 菜单->其它->互连网->gaim

5.添加新帐号。
点“所有帐号”，“增加”，协议选择MyICQ,然后输入你的用户名和密码，如果你还没有帐号，可以输入密码后选上下面的“在服务器注册新的用户”。Myicq服务器可以填myicq.cosoft.org.cn或者www.linuxfans.org
确定后点“登录/离开”就可以上线了，如果是注册新帐号，成功的话会出现对话框告诉你注册到的号码，再点工具菜单->协议动作->个人资料来设定你的资料，点搜索来加好友。
可以点“选项”，里面有代理的设置，myicq支持http和socks5代理。要显示昵称，选上设置->界面里的显示昵称选项。

5.使用。
点工具，协议动作，个人资料，这里可以修改你的资料，点头像图标还可以选择头像，修改好了点“修改”按钮就可以了。
协议动作里还有个搜索菜单，可以搜索添加好友。
点“工具”->暂时离开 这里可以选择你的状态，离开，隐身等,也可以选择custom，设置自动回复信息。
在好友图标上点右键可以查看资料，查看ip，发送文件等。
双击好友图标可以给他发送信息。
你可以通过搜索来创建群组，然后要别人加入进来聊天。注意，关闭聊天窗口或下线后会自动退出群组，如果群组里没有在线用户了，群组会自动消失。

6.和qq的并存。
如果是从源码安装，gaim-myicq将安装到/usr/local/bin/gaim
而qq的gaim为/usr/bin/gaim
touch ~/.gaim-qq
然后打/usr/bin/gaim -f ~/.gaim-qq
这样就可以让qq使用你自己定义的配置文件了。
你可以在桌面上做两个快捷方式，设置不同的命令和参数，这样两者就没有冲突了。

大家在使用过程中发现了bug或者有好的建议可以发邮件给我，或者在Myicq上告诉我。我在myicq.cosoft.org.cn服务器上的号码是10030.在linuxfans.org的帐号是10001.

胡正
2003.4.10
huzheng_001@163.com
http://forlinux.yeah.net
