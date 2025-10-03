# One Node

万物皆可搭节点 | Everything can be a proxy node.
端口说明
Lunes host 开放一个全端口，支持 TCP 和 UDP, 可以让 Xray 和 Hysteria 监听同一个端口。

Lunes host 官网地址：
https://lunes.host


节点类型	底层协议	TLS 证书
VLESS + Reality	TCP	偷证书
Hysteria	UDP	自签证书


一键安装脚本
curl -s https://raw.githubusercontent.com/vevc/one-node/refs/heads/main/lunes-host/install.sh |
env DOMAIN=容器地址 PORT=你容器端口 UUID=1ee897da-0887-4f7b-9dae-735a7298224b HY2_PASSWORD='自己设置密码' bash

在线密码生成器：https://1password.com/zh-cn/password-generator
