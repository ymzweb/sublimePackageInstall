# sublimePackageInstall
sublime论坛 https://forum.sublimetext.com/
1、Package Control安装目录切换
在sublime的安装目录下新建一个Data文件夹，将C:\Users\user_name\AppData\Roaming\Sublime Text 3目录下所有文件拷贝到Data下，重启sublime
2、Package Control的安装方式
https://github.com/HBLong/channel_v3_daily
(1)将文件Package Control.sublime-package放至Data/Installed Packages下
(2)将
"channels":
	[
		"D:/Program Files/Sublime Text 3/Data/Packages/channel_v3.json"(channel_v3.json存放目录)
	],
写至D:\Program Files\Sublime Text 3\Data\Packages\User\Package Control.sublime-settings中

emmet不生效问题，https://github.com/emmetio/pyv8-binaries/
pyv8-win64-p3文件夹改名为pyv8并放至 D:\Program Files\Sublime Text 3\Data\Installed Packages\下
