![输入图片说明](https://git.oschina.net/uploads/images/2017/0627/115003_625032bf_1285254.png "在这里输入图片标题")
**说明** 

提示：所有网站均需要以https方式打开,如访问www.google.com.hk网站，则需要输入https://www.google.com.hk

持续每周更新Hosts (包含Google、Gmail、Facebook、Twitter、Yahoo、Wikipedia、youtube等被墙的网站)文件。

大家如果有使用类似于go hosts的app，可以用我的这个网络源：https://gitee.com/lengers/connector/raw/master/hosts

 **适用系统** 

ios
Linux
Android
Mac
Windows


 **如何修改Hosts** 


Linux 

打开终端执行： vi /etc/hosts进行修改或执行：sudo wget https://git.oschina.net/lengers/connector/raw/cf435a8076cb44675f2b22c1f7a8d968c471b88f/hosts -O /etc/hosts

Android

如果是Android系统，用RE管理器（前提需要手机已Root）打开/system/etc/hosts目录，用下载好的hosts文件粘帖和覆盖该目录的hosts文件。然后通过开启飞行模式 -> 关闭飞行模式的方式使其生效。  **[ROOT工具
](http://zh.kingroot.net/)** 

Mac

如果是Mac系统，打开你的文件管理器（也就是Finder），然后，请按快捷键组合“Shift+Command+G”三个组合按键查找文件，并输入Hosts文件的所在路径：/etc/hosts，用下载好的hosts文件粘帖覆盖该目录的hosts文件。然后终端输入sudo killall -HUP mDNSResponder使其生效。

Windows

如果是Windows系统，用文本编辑器(如Notepad++|记事本)打开C:\Windows\System32\drivers\etc中的hosts文件，用下载好的hosts文件全部内容复制到C:\WINDOWS\system32\drivers\etc目录中的hosts文件中。或者用下载好的hosts文件粘帖和覆盖C:\WINDOWS\system32\drivers\etc目录中的hosts文件中。保存后通过开始 -> 运行 -> 输入cmd -> 在CMD窗口输入ipconfig /flushdns使其生效。


Connector 安卓客户端

使用方法：安装完成后打开APP，点击右边中间位置的“白色三角形”，选择“指定源”，再选择“网络”点击确定，之后再选择“添加Connector-网络-确定”，最后点击“一键Connector”即可（出现是否备份的界面时点击否，不然长期下去手机内存会越来越小）


 **更新时间** 

基本上每周都会更新一次。

 **联系方式** 

QQ/微信：303877543

E-mail: 303877543@qq.com

 **如果觉得本项目对你有帮助的话，点击右上角的捐赠，所得到的款项全部捐赠壹基金** 