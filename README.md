# SSR-Bash-Final
SSR多用户管理一键安装，带Web查询面板，支持流量/速度等限制
## 功能

一键开启、关闭SSR服务。

添加、删除、修改用户端口和密码。

自由限制用户端口流量使用。

自动修改防火墙规则。

自助修改SSR加密方式、协议、混淆等参数。

自动统计，方便查询每个用户端口的流量使用情况。

自动安装Libsodium库以支持Chacha20等加密方式。

## 安装

系统要求：
    CentOS 6+、Debian 6+、Ubuntu 14.04 +。

安装指令:

    yum install unzip wget #For Centos

    apt-get install unzip #For Debian和Ubuntu

安装多用户：

    wget -N --no-check-certificate https://raw.githubusercontent.com/szadamlee/SSR-Bash-Final/master/ssr.zip && unzip ssr.zip && cd SSR* && bash install.sh

安装完成后输入`ssr`指令进行管理。

![ssr管理指令](https://github.com/szadamlee/SSR-Bash-Final/raw/master/1.png)

记得开启`WEB`面板后在浏览器输入`http://ip:port`进行相关查询。
