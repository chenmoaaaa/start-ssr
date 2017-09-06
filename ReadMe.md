#By Defectink.
欢迎使用纯shell脚本技术的ShadowsocksR一键安装脚本。
本来创作该脚本初始目的是为了方便自己，即为自用。
后来放出来也希望能够帮助到有需要的朋友们。
脚本结构非常简单，使用的是纯Shell脚本语言。
大量使用的是if语句，个人对正则表达式理解程度还不到位，
导致了脚本的某些方面的不完善。以后会继续学习与修改的。
#说明
脚本默认为使用-d参数启动服务。
运行后该目录下会产生shadowsocksr文件夹以及shadowsocksr.zip
配置文件参数请参考

#主文件夹
主文件夹中拥有：
start.sh   --->主脚本
switch.sh   --->额外启动停止服务脚本（默认主脚本已启动服务）
ReadMe.md   --->本说明文档
other   --->如下

#other文件夹
other文件夹中存放的是独立分开的脚本部分。
对于后续的修改可能会有作用。
其中：
git.sh	 -->检查git安装以及git to ShadowsocksR
setup.sh   --->创建用于运行的config.json
python.sh   --->检查python安装以及运行ShadowsocksR服务端

#声明
此脚本只适用于Ubuntu/Debian
本脚本安装的ShadowsocksR为Python版，且本脚本会绿色运行
在您的服务器上，不会执行安装操作。
ShadowsocksR为原作者Fork而来。
个人不承担运行服务后的结果。

#若无法正常运行
请尝试给予脚本可执行权限
或者尝试通过sh 运行脚本
请使用管理员权限运行