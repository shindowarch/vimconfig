# vimconfig
some config file about vim ,to make vim more easy to use


Install:
 for Linux:
    ./install.sh
 for Windows:
   double click install.bat 


Instructions:
1.首先要安装好ctags 和 cscope
    sudo apt-get install ctags cscope
2.按键说明
    <F1>弹出中文帮助窗口,输入:q退出
    <F2>创建工程tags并放入当前目录下的project-vim文件夹中，并自动加载tags.
    <F3>在界面左部打开一个窗口,显示当前文件中的宏、全局变量、函数、类等信息，鼠标点击时就会跳到相应的源代码所在的位置-Taglist,再按一遍退出.
    <F4>在界面右部打开代码资源管理器-NERDTree,再按一遍退出. 
    <F5>超快查找文件-CtrlP,按ESC退出.
    <F6>打开最近使用的文件列表,输入:q退出.
    <F12>在函数名上按F12键，自动生成函数的注释.
    在vi底部命令行输入  :vsp 空格加tab键可罗列出当前目录下所有文件，继续键入文件名可打开你刚输入的文件并与之前的窗口分屏显示.
    在vi底部命令行输入  :e   空格加tab键可罗列出当前目录下所有文件，继续键入文件名可将当前窗口切换至你键入的文件窗口.
3.较v1.0增加的功能
    <1>安装了pathogen插件管理工具
    <2>安装了代码检查工具syntastic-3.7.0,每次打开文件的时候会主动触发检查，不用按键触发.
4.较v2.0增加的功能
     <1>安装了powerline，使状态栏更加多功能.

