# Mactype造成win10周年更新黑屏的解决方法
mactype里自带的EasyHK32.dll以及EasyHK64.dll版本过低,导致新系统版本号无法使用の解决办法:

> 在更新前需要做的

1）关闭Mactype：打开 MacWiz.exe，选择“不使用自动加载”；

2）开始安装更新；

3）更新安装成功。进入系统之后，下载此压缩包 链接：http://pan.baidu.com/s/1o8wAeEY 密码：myic 用压缩包中的EasyHK32.dll EasyHK64.dll，替换电脑中Mactype文件夹中的同名文件；

4）打开Mactype，即可正常使用注册表加载及托盘独立加载。

> 如果没有做上面中的操作，导致更新后电脑出现无限蓝屏、无限循环重启等情况。

1）在电脑进入系统的过程中（转圈圈加载的时候），长按电源键强制关机（硬关机）。重复两次，下次开机电脑就会进入自动修复界面；
（如果没有进入自动修复，则你强制关机的时机错了。一定要在进入系统的时候长按电源键关机，才属于硬关机）；

2）进入自动修复界面后，选择疑难解答→高级选项→回退到以前的版本。 这样就能删除最新更新内容，回到安装最新更新前的版本。且“不会对电脑内的其他文件产生影响”。

3）成功回退之后，便进入到了之前的状态。接下来就按照上面更新前的步骤来即可。

[转自【碩骅】的帖子](http://tieba.baidu.com/p/4711944449)

![](https://o2mu9ei56.qnssl.com/win10.jpg)
