# xray
## 介绍
### install.sh
- xray安装脚本，适用于centos7+/debian9+/ubuntu16.04+
- 调用xray官方安装脚本
- 使用vless+tcp+xtls模式
- 回落使用nginx，配置伪装站

### install_wp.sh
- xray安装脚本，适用于centos7
- 调用xray官方安装脚本
- 使用vless+tcp+xtls模式
- 回落使用nginx，配置wordpress

## install_triple_config.sh使用
bash <(curl -Ls https://raw.githubusercontent.com/atrandys/xray/main/install_triple_config.sh)

## install.sh使用
bash <(curl -Ls https://raw.githubusercontent.com/atrandys/xray/main/install.sh)

## install_wp.sh使用
bash <(curl -Ls https://raw.githubusercontent.com/atrandys/xray/main/install_wp.sh)

## client使用
- OpenWrt
  - [PassWall](https://github.com/xiaorouji/openwrt-passwall)
- Windows
  - [v2rayN](https://github.com/2dust/v2rayN)
- Android
  - [v2rayNG](https://github.com/2dust/v2rayNG)
- iOS / Mac
  - [Shadowrocket](https://apps.apple.com/app/shadowrocket/id932747118)


