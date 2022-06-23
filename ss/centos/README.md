# Centos 7/8 install shadowsocks

```
bash <(curl -sL https://raw.githubusercontent.com/hijkpw/scripts/master/centos_install_ss.sh)
```

### 本次搭建 Shadowsocks / SS 共完成了以下几件事情：

- 更新系统到最新版
- 安装 bbr 加速模块
- 安装 SS 并设置开机启动

### 其它命令
1. 查看ss运行状态
```
bash <(curl -sL https://raw.githubusercontent.com/hijkpw/scripts/master/centos_install_ss.sh) info
```
2. SS 管理命令：
```
启动：systemctl start shadowsocks-libev
停止：systemctl stop shadowsocks-libev
重启：systemctl restart shadowsocks-libev
```
3.  更改密码、端口、加密方式最简单方法：重新运行一次安装脚本

4. 更新 SS 到最新版：重新运行一键脚本

5. 卸载 SS：
```
bash <(curl -sL https://raw.githubusercontent.com/hijkpw/scripts/master/centos_install_ss.sh) uninstall
```