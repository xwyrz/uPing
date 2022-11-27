# uPing
一个24小时监测VPS延迟的工具

## 警告

目前正在测试阶段，请勿用于生产环境！

## 依赖安装

Debian / Ubuntu :

    apt-get update
    apt-get install python3 wget tmux -y

CentOS / RHEL :
  
    yum install python3  wget tmux -y

## 使用方法

    tmux new -s uping
    wget -N --no-check-certificate https://raw.githubusercontent.com/xwyrz/uPing/master/uping.py
    python uping.py
  
## 截图

  ![uPing.png](uPing.png)
