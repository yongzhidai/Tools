# Tools
GameServer环境搭建工具包

apache-tomcat-7.0.57
	tomcat程序，需要做如下修改：
		conf/server.xml中添加指向GameServer的Context标签
		conf/context.xml 中添加数据源
		conf/web.xml添加数据源生命

apache-mina-2.0.9-bin
apache-mina-2.0.9-src
			GameServer中用到的mian包以及源码
			
ibatis-2.3.4.726
			GameServer中使用的持久层框架
			
IbatorForEclipse1.2.1
			eclipse插件，用于根据配置文件，自动生成ibatis的sqlmap文件以及相关dao代码
tomcatPluginV331
			eclipse插件，用于启动tomcat并配置相关参数的工具