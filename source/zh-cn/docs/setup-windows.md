title: 安装Windows版钱包
comments: false
---

# 下载钱包客户端
到官网[https://mvs.org/#download](https://mvs.org/#download)下载Windows钱包客户端，本客户端目前支持Windows 64位系统。

安装包有标准版和数据包版，数据包版为自带数据库的安装版本，可以极大节省第一次的区块同步时间，建议新用户下载安装；由于数据包版可能会覆盖原始数据，建议老用户安装标准版。请根据您的情况选择合适的安装包。

# 安装钱包客户端
双击安装程序，按照提示的步骤进行安装，安装完毕后，在桌面出现钱包的快捷启动图标，双击钱包启动程序，即可打开钱包登陆页面。

***
# 进阶使用
## 了解钱包默认安装目录和数据存储目录
默认安装目录：     C:\Program Files (x86)\Metaverse
默认数据存储目录： %HOMEPATH%\AppData\Roaming\Metaverse

## 如何退出钱包程序
通过在托盘图标右击钱包图标，选择 Exit 菜单退出钱包。
通过任务管理器查看钱包进程 mvsd.exe 和 mvstray.exe 不在运行，否则结束之。

## 如何备份钱包数据
钱包数据默认存储在目录 %HOMEPATH%\AppData\Roaming\Metaverse 中。为了数据安全，请定期备份这个目录，特别是在进行钱包卸载、重新安装、升级安装时。

## 如何卸载钱包
进入钱包默认安装目录 C:\Program Files (x86)\Metaverse， 如果你修改了安装目录请进入相应的安装目录中，通过双击 uninst.exe 运行钱包卸载程序。

## 如何重新安装钱包
重新或者升级安装钱包，请先退出钱包程序，做好钱包数据备份，然后卸载老钱包程序，再双击新的钱包安装程序进行安装。

