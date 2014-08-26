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

###开发流程

开发者流程

- 开发者是指现在TeamTalk的开发人员，或者以后我们信任的贡献者转化而成的开发人员。

- 要成为开发者，需要在github上注册账号, 然后由管理者加入到相应项目的collaborators列表

- 开发主要用到master和develop两个分支， 平时开发都在develop分支上，只有代码
达到一个milestone的stable状态，才把develop分支merge到master分支

- 有时开发者可能想实现一个比较cool的feature，可以建立一个feature_x分支，
测试稳定后merge到master

贡献者流程

- 贡献者是指非TeamTalk项目组成员的对开源项目贡献代码的开发人员

- 贡献者需要先在github上Fork一个项目，然后在Fork的项目上提交代码，
再通过Pull Request把修改通知给项目开发者，由开发者code review后，
决定是否merge进入master分支， 具体可参考: [github协作流程](http://www.worldhello.net/gotgithub/04-work-with-others/010-fork-and-pull.html)
		
###开源协议
[Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html) 

###Remark
![](https://raw.githubusercontent.com/mogutt/TTiOSClient/develop/pic/we-need-you.png)
