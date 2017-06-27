![输入图片说明](https://git.oschina.net/uploads/images/2017/0627/110115_f655e4cf_1285254.png "在这里输入图片标题")
###  
**说明** 

提示：所有网站均需要以https方式打开,如访问www.google.com.hk网站，则需要输入https://www.google.com.hk

持续每周更新Hosts (包含Google、Gmail、Facebook、Twitter、Yahoo、Wikipedia、youtube等被墙的网站)文件。



 **适用系统** 

Unix
Linux
Android
Mac
Windows


 **如何修改Hosts** 


Linux 

打开终端执行： vi /etc/hosts进行修改

Android

如果是Android系统，用RE管理器（前提需要手机已Root）打开/system/etc/hosts目录，用下载好的hosts文件粘帖和覆盖该目录的hosts文件。然后通过开启飞行模式 -> 关闭飞行模式的方式使其生效。  **[ROOT工具
](http://zh.kingroot.net/)** 

Mac

如果是Mac系统，打开你的文件管理器（也就是Finder），然后，请按快捷键组合“Shift+Command+G”三个组合按键查找文件，并输入Hosts文件的所在路径：/etc/hosts，用下载好的hosts文件粘帖和覆盖该目录的hosts文件。然后终端输入sudo killall -HUP mDNSResponder使其生效。

Windows

如果是Windows系统，用文本编辑器(如Notepad++|记事本)打开C:\Windows\System32\drivers\etc中的hosts文件，用下载好的hosts文件全部内容复制到C:\WINDOWS\system32\drivers\etc目录中的hosts文件中。或者用下载好的hosts文件粘帖和覆盖C:\WINDOWS\system32\drivers\etc目录中的hosts文件中。保存后通过开始 -> 运行 -> 输入cmd -> 在CMD窗口输入ipconfig /flushdns使其生效。

注意：如果遇到无法保存，请右键hosts -> 属性 -> 安全，然后选择你登陆的用户名，最后点击编辑，勾选"写入"即可。

注意：如果hosts文件中已经有内容，那么请把已有的内容追加到hosts文件末尾。

 **注意：Connector客户端根据反馈得知部分机型会出现无法下载显示红X，此时重新选定网络源之后再选择“添加Connector-网络-确定”，然后再点击一键安装** 


 **更新时间** 

基本上每周都会更新一次。


 **联系方式** 

E-mail: 303877543@qq.com