weibo
=====

## 环境安装

### Eclipse IDE for Java EE Developers
版本：Kepler

下载地址：[http://www.eclipse.org/downloads/packages/eclipse-ide-java-ee-developers/keplersr2](http://www.eclipse.org/downloads/packages/eclipse-ide-java-ee-developers/keplersr2)

### Tomcat 
版本：7.0

下载地址：[http://tomcat.apache.org/download-70.cgi](http://tomcat.apache.org/download-70.cgi)

### MongoDB  
版本：2.6

下载地址：[http://www.mongodb.org/downloads](http://www.mongodb.org/downloads)

### Git
下载地址：[http://msysgit.github.io/](http://msysgit.github.io/)

### *TortoiseGit（可选）*
*下载地址：[https://code.google.com/p/tortoisegit/wiki/Download?tm=2](https://code.google.com/p/tortoisegit/wiki/Download?tm=2)*

安装时请选择：


## 配置工作
1. 从 Git 仓库中克隆源代码  

	首先在 oschina 注册一个 git 账号，注册地址：[https://git.oschina.net/signup](https://git.oschina.net/signup)
	
	注册完成后请将 ID 发给项目管理员，以将您加入项目管理组。

	确认您已经在项目管理组后，在终端中运行：

		git clone https://git.oschina.net/whypro/Weibo.git
	
	按照提示输入注册时的用户名和密码后等待克隆成功。

	项目在线管理地址：[https://git.oschina.net/whypro/Weibo](https://git.oschina.net/whypro/Weibo)

2. 将代码导入 Eclipse 工作区  
3. 启动 MongoDB

		mongod --dbpath "../data"
	
	其中 "../data" 为数据库路径，请保证该目录存在，如果是 Windows 请使用 mongod.exe

4. 配置 Tomcat
5. 运行

## 代码编写
请参照：[http://my.oschina.net/u/1013711/blog/207987](http://my.oschina.net/u/1013711/blog/207987)

## 任务分配
请移步设计文档，平均每人一个模块，具体任务待定。
