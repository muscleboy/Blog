#  Ubuntu16.04安装为知笔记
---
##  错误示范：
* sudo add-apt-repository ppa:wiznote-team
* sudo apt-get update
* sudo apt-get install wiznote
这么安装的版本不是最新的，会有密码错误bug，
重置也没用
---
##  解决办法：
* 直接在[官网](https://url.wiz.cn/u/Wizlinux) 下载绿色版，
下载的文件是.AppImage格式的.
* 至于什么是AppImage格式，可以在了解一下,[AppImage](https://ubuntuqa.com/article/546.html) 
* 简单来说，AppImage是Linux软件包的发行格式，可以通过命令来安装
* chmod a+x example.AppImage
* ./example.AppImage
稍等一下就能登录了。
