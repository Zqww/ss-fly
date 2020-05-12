# 1.下载一键搭建ss脚本文件
如果提示 bash: git: command not found，则先安装git：
 Centos执行这个： yum -y install git
 Ubuntu/Debian执行这个： apt-get update && apt-get -y install git
 
# 2.运行搭建ss脚本代码

ss-fly/ss-fly.sh -i 密码 端口(默认1024）

# 3.相关操作

 启动：/etc/init.d/ss-fly start
 停止：/etc/init.d/ss-fly stop
 重启：/etc/init.d/ss-fly restart
 状态：/etc/init.d/ss-fly status
 查看ss链接：ss-fly/ss-fly.sh -sslink
 修改配置文件：vim /etc/shadowsocks.json
 卸载：ss-fly/ss-fly.sh -uninstall
 



