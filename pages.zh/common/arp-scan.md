# arp-scan

> 发送 ARP 数据包到特定主机（指定 IP 地址或主机名），来扫描本地网络。
> 更多信息：<https://github.com/royhills/arp-scan>.

- 扫描当前本地网络：

`arp-scan {{[-l|--localnet]}}`

- 扫描带有自定义位掩码的 IP 网络：

`arp-scan {{192.168.1.1}}/{{24}}`

- 扫描自定义范围内的 IP 网络：

`arp-scan {{127.0.0.0}}-{{127.0.0.31}}`

- 扫描带有自定义子网掩码的 IP 网络：

`arp-scan {{10.0.0.0}}:{{255.255.255.0}}`
