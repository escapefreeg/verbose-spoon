# Actions-OpenWrt
## learn from P3TERX [link](https://github.com/P3TERX/Actions-OpenWrt)

## 22-12-10 lede K3 22.03 waiting
### config
- target: K3
- source code: lede
- source code version: master_newest
- have cat: no
- config name: lede_config.config

## 22-10-03 offical x64 22.03 waiting
### config
- target: x64
- source code: offical
- source code version: branch_openwrt-22.03_newest
- have cat: yes
- config name: .x64allv1
### additional info
- ubuntu version: 22.04
- firewall and dnsmasq
- no wget, frpc and frps

## 22-10-03 offical x64 22.03 success
### config
- target: x64
- source code: offical
- source code version: branch_openwrt-22.03_newest
- have cat: no
- config name: .x64change2
### additional info
- ubuntu version: 22.04
- firewall and dnsmasq

## 22-10-03 offical x64 22.03 success
### config
- target: x64
- source code: offical
- source code version: branch_openwrt-22.03_newest
- have cat: no
- config name: .x64default
### additional info
- ubuntu version: 22.04

## 22-09-30 offical x64 22.03 failed
### config
- target: x64
- source code: offical
- source code version: branch_openwrt-22.03_newest
- have cat: yes
- config name: .config
### additional info
- ubuntu version: 22.04
- wget x2
- frpc,frps
- luci-nginx