### 需求

你需要安装以下软件并运行:
 - [Microsoft Flight Simulator](https://www.flightsimulator.com) (2020/2024 version) (仅在2024 SU3 BETA中进行过测试)
 - [Inibuilds's A350](https://inibuilds.com) (WebRemote已经过1.0.5版本的测试)
 - [FSUIPC7 for MSFS](http://www.fsuipc.com) (免费版即可)
 - [FSUIPC WebSockets Server](http://fsuipcwebsockets.paulhenty.com) (已经在FSUIPC中预装，不过你需要在菜单项“Add-ons”中点击“Auto-Start”启用)


### 本地安装

1. 在Release下载`a350-webremote-xxx.zip`并解压至本地非中文路径文件夹
2. 将`extras/FSUIPC7/`目录下的`myOffsets.txt`文件复制到你的FSUIPC7安装目录下，并重启FSUIPC
3. 在`web`文件夹中找到`index.html`并双击用浏览器打开
4. 如果你的FSUIPC WebSockets使用默认设置运行，WebSocket URL一栏输入`ws://localhost:2048/fsuipc/`后点击“Connect”
