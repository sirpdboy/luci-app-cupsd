## 访问数：[![](https://visitor-badge.glitch.me/badge?page_id=sirpdboy-visitor-badge)] [![](https://img.shields.io/badge/TG群-点击加入-FFFFFF.svg)](https://t.me/joinchat/AAAAAEpRF88NfOK5vBXGBQ)
    
![screenshots](https://raw.githubusercontent.com/sirpdboy/openwrt/master/doc/说明1.jpg)

## 编译说明 

git clone https://github.com/sirpdboy/luci-app-cupsd.git

cd openwrt

echo "src-git cups https://github.com/sirpdboy/luci-app-cupsd.git" >> feeds.conf.default


./scripts/feeds update -a

./scripts/feeds install -a

make menuconfig 

set Network  ->  Printing  ->  cups  


![screenshots](https://raw.githubusercontent.com/sirpdboy/openwrt/master/doc/说明2.jpg)

#  other cups:

##  https://github.com/Gr4ffy/lede-cups

##  https://github.com/TheMMcOfficial/lede-cups

![screenshots](https://raw.githubusercontent.com/sirpdboy/openwrt/master/doc/说明3.jpg)

|     <img src="https://img.shields.io/badge/-支付宝-F5F5F5.svg" href="#赞助支持本项目-" height="25" alt="图飞了😂"/>  |  <img src="https://img.shields.io/badge/-微信-F5F5F5.svg" height="25" alt="图飞了😂" href="#赞助支持本项目-"/>  | 
| :-----------------: | :-------------: |
|![xm1](doc/支付宝.png) | ![xm1](doc/微信.png) |

[![](https://img.shields.io/badge/TG群-点击加入-FFFFFF.svg)](https://t.me/joinchat/AAAAAEpRF88NfOK5vBXGBQ)

