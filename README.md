## oct_chat
一对一聊天系统

#### 启动
linux系统在项目运行目录(public)下执行命令：php start.php start
windows系统使用项目运行目录(public)下的bat脚本启动进程

#### 功能介绍
###### 登录注册
登录时如果登录了未注册的帐号则自动注册并登陆

###### 登录广播
当会员登录后，所有在线会员会收到会员登录的广播

###### 在线会员列表
所有在线会员会显示在在线会员列表中

###### 联系列表
所有联系过的会员均在此显示；

当会员想你发送信息后，联系列表状态改变并在列表中增加未读消息；

读取完未读消息后状态恢复；

###### 聊天
当前仅可以发送文字；

#### 安装备注
数据库创建成功后，如果数据库名称不是oct_chat，请在application/database.php和applocation/index/controller/Events.php文件中修改数据库配置