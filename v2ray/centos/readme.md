# 一键安装V2ray
```
bash <(curl -sL https://raw.githubusercontent.com/hijkpw/scripts/master/centos_install_v2ray.sh)
```
### 本次搭建 V2Ray 共完成了以下几件事情：

- 更新系统到最新版
- 安装 bbr 加速模块
- 安装 SS 并设置开机启动

### 其它配置
1. 查看 v2ray 配置/运行状态：
```
bash <(curl -sL https://raw.githubusercontent.com/hijkpw/scripts/master/centos_install_v2ray.sh) info
```
2. v2ray 管理命令：
```
启动：systemctl start v2ray
停止：systemctl stop v2ray
重启：systemctl restart v2ray
```
3. 更改端口、alterid 最简单的办法：重新运行一键脚本

4. 更新 v2ray 到最新版：
```
bash <(curl -sL https://raw.githubusercontent.com/hijkpw/scripts/master/goV2.sh)
```
（提示“装不上 daemon ”不用管，systemctl restart v2ray重新启动 v2ray 就好了）

5. 卸载 v2ray：
```
bash <(curl -sL https://raw.githubusercontent.com/hijkpw/scripts/master/centos_install_v2ray.sh) uninstall
```