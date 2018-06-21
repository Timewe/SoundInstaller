#诗蓝LOL语音助手



诗蓝LOL语音助手可以最快2s内一键更换多国语音包（包括日服、韩服、俄服、法语、希腊语、英语等等），安全、免费、无封号！语音资源提取自PBE最新语音，可以2到3个版本内无需进行更新！并采用补丁更新方式以最大化减少更新时间，持续更新并后续将加入更多模块。 

##官方网站

http://www.timeweii.com/sound.html
  

##软件预览图：
![输入图片说明](https://gitee.com/im-timewe/SoundInstaller/raw/master/preview/pre.gif "在这里输入图片标题")


##软件介绍：

1. 关于软件项目：  软件基于.NET FrameWork4.7开发，因此运行此程序必须电脑已经提前安装4.7或者更高版本的.NET Framework框架，否则程序无法正常运行！整体采用MVVM架构【本萌新水平极差，代码部分不堪入目~如果看到源码的话，很大可能致使程序员放弃码农而改为直播女装(＞﹏＜)

2. UI界面相关： UI界面部分借鉴了微软的[Microsoft-Teams ](https://products.office.com/en-us/microsoft-teams/group-chat-software)产品，UI设计什么的真是好难的啦o(≧口≦)o，所以...额......，然后界面布局上面参考了Accelerider团队的[AcceleRider for Windows ](https://github.com/Accelerider/Accelerider.Windows)项目,界面元素及视图控件引用了James Willock的[Material Design In XAML Toolkit](https://github.com/ButchersBoy/MaterialDesignInXamlToolkit)，不知道会不会被大大们给打死【强忍泪水.....

3. 关于更新维护：关于软件更新，此项目由我个人维护的，语音包的更新和软件的更新优化将会不定时更新，软件采取自动更新的方式（无法自动更新请手动下载【解压覆盖文件】），语音包模块采用手动下载方式（因为文件比较大），语音补丁可以自动更新也可以手动下载导入，当无法自动更新请切换到手动下载

4. 游戏版本更新后： 游戏版本更新之后，建议打开本软件重新应用一次语音，以避免一些不必要的麻烦

5. 温馨提示： 诗蓝LOL语音助手不存在收费版本！任何向你盗卖或引导你购买的行为，请自己辨别并举报，使用前请了解：诗蓝LOL语音助手永久免费分享！


##Dependencies：

[Material Design In XAML Toolkit](https://github.com/ButchersBoy/MaterialDesignInXamlToolkit)                            

[Fantome.Libraries.League](https://github.com/LoL-Fantome/Fantome.Libraries.League)                                    

[AcceleRider for Windows](https://github.com/Accelerider/Accelerider.Windows)                                            

[Unity Container](https://github.com/unitycontainer/unity)                                     

[Newtonsoft.Json](https://www.newtonsoft.com/json)                                                             

[Prism](https://github.com/PrismLibrary/Prism)                             

[refit](https://github.com/paulcbetts/refit)


##软件操作预览图：


1. 导入语音模块操作：

![输入图片说明](https://gitee.com/im-timewe/SoundInstaller/raw/master/preview/import-preview.gif "在这里输入图片标题")


2. 安装语音操作：

![输入图片说明](https://gitee.com/im-timewe/SoundInstaller/raw/master/preview/install-preview.gif "在这里输入图片标题")



3. 删除语音操作：

![输入图片说明](https://gitee.com/im-timewe/SoundInstaller/raw/master/preview/delete-preview.gif "在这里输入图片标题")


##文件下载地址：


####主程序下载地址：   

 https://gitee.com/im-timewe/SoundInstaller/raw/master/诗蓝LOL语音助手-public.rar


####.NET Framework4.7框架（必须安装！已安装可跳过此安装）：

微软官网下载链接：    https://www.microsoft.com/net/download/thank-you/net472



##使用帮助文档            

####基本使用步骤：

   
下载软件-->解压到本地磁盘-->双击【开始.bat】文件（此bat文件会创建桌面快捷方式）-->双击桌面快捷方式打开助手-->进入主界面后按照提示下载模块-->模块下载完成后，点击菜单》导入语音模块按钮-->拖拽或者选择文件进行导入-->回到主界面点击安装语音包即可 
                                    


####常见问题解决办法：

1. 双击桌面快捷方式后提示软件未响应或停止工作？

答：你可能未安装.NET Framework4.7.2框架，.NET 4.7.2框架下载地址：[微软官网下载地址](https://www.microsoft.com/net/download/thank-you/net472)  

2. 这里是列表文本安装 Microsoft.NET Framework 4.7 时，安装被阻止，无法继续？

答：因为你的计算机缺失的 d3dcompiler 导致的更新受阻，这里有微软官方解决教程：[查看微软官方教程 ](https://support.microsoft.com/zh-cn/help/4020302/the-net-framework-4-7-installation-is-blocked-on-windows-7-windows-ser)

3. 提示以管理员身份运行并重新操作？

答：可能当前权限不够，无法完成操作，请退出助手并重新以管理员身份运行本软件（右键软件图标—属性—兼容性—勾选管理员身份运行），或者直接右键软件图标--以管理员身份运行）              。  

4. 导入语音包时提示文件已损坏，尝试重新下载？

答：可能你的语音模块未下载完整，因为导入的时候会校检文件Md5值，以判断文件的完整性。你可以尝试检查是否下载完整，并尝试重新导入，如果还是提示，请重新下载语音模块   

5. 提示检查网络连接或者写入配置文件失败请重试？

答：可能你当前网络状况不好，导致获取服务器信息失败，请检查网络连接。写入配置文件失败的请尝试管理员身份重新运行助手  

6. 鼠标悬停在卡片上时，界面卡顿？

答：因为助手采取的动态获取数据的方式，鼠标悬停的时候实际上已经在处理数据，此时会请求远程数据，如果网络状态不佳可能会造成卡顿，一般来说不会出现这种现象的
