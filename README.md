###项目背景
	随着蘑菇街由导购向电商转型，蘑菇街自己的IM也应运而生，IM起初只是用于商家和
	买家之间沟通的工具。后面我们问自己，既然已经有了用于客服的IM，为什么不自己
	做一个IM，用于公司内部的沟通工具，来替换RTX呢，然后就有了TT(TeamTalk)
	的雏形，现在蘑菇街内部的IM工具都是TT来完成的。随着TT的逐渐完善，我们再次
	决定把TT开源，来回馈开源社区，我们希望国内的中小企业都能用上免费开源的
	IM内部沟通工具。

###系统环境
	服务器端: Linux
	客户端支持: Windows，Mac, iOS, Android

###子系统介绍
	-TTCppServer
	TT的服务器，包括登陆分配，长连接接入，消息路由，文件传输, 
	文件存储等功能的支持	
	
	-TTJavaServer
	TT的服务器，只要是作为TT服务器操作MySQL和Redis的代理服务器
	
	-TTWinClient
	Window客户端[界面截图]
	
	-TTMacClient
	Mac系统客户端[界面截图]
	
	-TTIOSClient
	iOS客户端[界面截图]
	
	-TTAndroidClient
	Android客户端[界面截图]
	
###编译安装
	详见INSTALL文件
	
###开源协议
[Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html) 

###Remark
![](https://raw.githubusercontent.com/mogutt/TTiOSClient/develop/pic/we-need-you.png)
