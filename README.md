## ansible

ansible的核心组件：
	ansible core
	host ivertory：主机列表
	core modules 核心模块
	custom modules 自定义模块
	playbook （支持yaml，和jinjia2模板语言）
	connect plugin
ansible的特性：
	ansible基于python语言实现，由Paramiko，PyYAML和Jinjia2三个关键的模块:
	
	部署简单：没有agent端
	默认使用SSH协议：
				1) 基于秘钥认证
				2) 在inventory文件中指定账号和密码
	主从模式：
		master：ansible，ssh client
		slave： ssh server
	支持自定义模块：支持各种编程语言
	支持Playbook
基于“模块”完成各种“任务”