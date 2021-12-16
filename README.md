# This repository is no longer maintained


git clone https://github.com/sirpdboy/luci-app-cupsd.git

cd openwrt

echo "src-git cups https://github.com/sirpdboy/luci-app-cupsd.git" >> feeds.conf.default


./scripts/feeds update -a

./scripts/feeds install -a

make menuconfig 

set Network  ->  Printing  ->  cups  



#  other cups:

##  https://github.com/Gr4ffy/lede-cups

##  https://github.com/TheMMcOfficial/lede-cups
