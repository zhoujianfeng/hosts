# hosts

  最新更新于：2017-10-19  @author  重剑无锋
  
  上次更新于：2017-01-17  @author  重剑无锋
  
  
# 修改hosts后立即生效的方法

Windows
开始 -> 运行 -> 输入cmd -> 在CMD窗口输入
   ipconfig /flushdns

Linux 终端输入
     sudo rcnscd restart
对于systemd发行版，请使用命令
    sudo systemctl restart NetworkManager
 

Mac OS X终端输入
   sudo killall -HUP mDNSResponder

Android
   开启飞行模式 -> 关闭飞行模式

通用方法
   拔网线(断网) -> 插网线(重新连接网络)
