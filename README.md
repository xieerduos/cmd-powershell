### win10常用的快捷键

```java
Win  +  R   调出 运行，输入cmd 或者 powershell  即可打开 命令 窗口
Win  +  S  激活Cortana
Win  +  C  语音激活Cortana
Win  +  A  激活操作中心

Win  +  D  激活操作中心
Win  +  Tab  激活任务视图
Win  +  E    打开文件管理器

Win  +  L    锁屏
Win  +  X    打开开始菜单，打开高级用户功能
Win  +  I    打开Win10设置

Win  + Ctrl + D 创建一个虚拟桌面
Win  + Ctrl + F4 关闭虚拟桌面
Win  + Ctrl + 左/右  切换虚拟桌面
Win  + 1/2/3   打开任务栏中固定的程序，1代表任务栏中的第一个应用图标

Win  + E   打开文件管理文件夹
Alt  + F4    关闭当前活动窗口
```
### win10常用的命令
##### 前面的 $ 代表的是当前是命令行模式运行后面的命令
```s
$  cd  desktop            切换到桌面
$  md  my-example   创建一个 my-example
$  cd  my-example     进入 my-example 文件夹
$  code  .                    此处打开 vscode 编译器
$  dir                          查看目录
$  del                         至少删除一个文件，后面接要删除的文件或者文件夹
$  rmdir    filename   删除文件目录，cmd可用来删除文件夹。powershell的化，del和rmdir都有用
$  md   src  js  css     创建3个文件夹
$  mkdir  src  js  css  创建3个文件夹
$  cls                         清屏
$  echo  >dist/index.html   在dist文件夹下创建一个index.html文件
$  exit                       关闭 cmd 窗口
$   taskkill   /f   /im  chrome.exe    关闭chrome.exe进程（程序）
	/f 是强行关闭的意思
	/im  指的是程序的名字
$  tasklist   /svc   查看计算机当前的 运行的 应用程序


$  start opera  http://127.0.0.1:3000     打开Opera浏览器，地址栏地址后面写的哪一个
$  start chrome http://127.0.0.1:3000   打开 chrome 浏览器 
$  start firefox  http://127.0.0.1:3000    打开 firefox 浏览器 
$  start iexplore  http://127.0.0.1:3000  打开IE浏览器 
```