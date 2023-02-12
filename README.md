# 官网
https://www.mongodb.com/

### 下载地址
https://www.mongodb.com/try/download/community

### 查看系统安装的所有Shell
cat /etc/Shells

### 查看当前使用的Shell
echo $SHELL

### 修改默认Shell为zsh
chsh -s /bin/zsh 


### 配置环境变量
在`.bash_profile`中


### 启动和暂停MongoDB
mongod --dbpath="数据存储目录"
默认会占用27017端口

## 测试是否连接成功

1. 先启动 mongod --dbpath="" 命令。（启动mongoDB数据库服务）
2. 再启动 mongo 命令，如果命令不报错，说明已经启动了。