# 解决 wiringpi 不支持 arm64 系统的问题

众所周知，wiringpi 很早就不再更新了，虽然树莓派官方系统即使是 arm64 系统也有对 arm32 的支持。解决方案很简单，只要用搜索引擎一搜，就会发现早就有 [大佬](https://github.com/guation) 把 wiringpi 的仓库 fork 下来继续维护了。[wiringpi非官方fork仓库地址](https://github.com/guation/WiringPi-arm64)，我们只需要进入 release 页面下载大佬打包好的 .deb 按照仓库教程安装即可。

