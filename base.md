# 基本

## Sublime text 3 中Package Control的安装与使用方法

因为在线安装容易出问题，所以采用手动安装

Package Control 主文件下载

1. 下载地址：https://github.com/wbond/sublime_package_control 
   选择Download ZIP

2. 解压到当前文件，不是解压到package_control-master，把文件名改为Package Control

3. Preferences->Brows Packages,复制刚才的“Package Control”文件到该目录下面

4. 打开sublime text 3编辑器，在菜单->preferences->Package Settings和Package Control选项，就说明安装package control成功了

5. 快捷键 Ctrl+Shift+P（菜单 – Tools – Command Paletter），输入 install 选中Install Package并回车，输入或选择你需要的插件回车就安装了（注意左下角的小文字变化，会提示安装成功）。


## 打开GBK编码的文件乱码？
1. 在菜单->preferences->Package Settings->Settings - User
2. 点击Package Control，上面会出来一个输入框，我们输入install，就会自动有提示那个install package，我们点击一下install package，输入框会消失，稍等一下又会弹出个输入框。
3. 输入ConvertToUTF8点击下载，重启下Sublime Text 3

## sublimet text3 编辑markdown
需要下载安装Markdown Editing和Markdown Preview 插件，这里就不多说了，直接看博客走起 
http://www.cnblogs.com/IPrograming/p/Sublime-markdown-editor.html