1、软件共包括四部分内容：
	jre32：Java运行环境
	auto-adsl-32bit.exe：软件入口，点击运行软件
	config.properties：配置文件，配置宽带连接名、账号、密码
	README.txt：说明文档
2、使用前请先创建ADSL拨号连接
3、使用前请先配置config.properties文件中的参数（区分大小写）：
	adslName：adsl连接名
	adslAccount：adsl账号
	adslPassword：adsl密码
	listenPort：软件使用的端口（默认设置的端口即可）
4、远程控制：
	连接adsl命令：ip:port/connectNetwork
		连接成功返回：已成功建立连接
		连接失败返回：宽带连接状态码（如691） + 提示信息
	断开adsl命令：ip:port/shutdownNetwork
		断开返回：已断开
  ip表示使用软件的计算机的ip
  port表示软件使用的端口
