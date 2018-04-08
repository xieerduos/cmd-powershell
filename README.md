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
### 使用方法
#### 注意：
>>> 如果命令正在执行中，可以使用 Ctrl + C 来终止命令，或者退出命令

#### 具体的使用方法
```s
以前都是 打开vscode  都是，找到vscode图标，单击vscode图标，在vscode中打开 项目文件夹 。
用命令的步骤是：
1-Ctrl + R   快捷键，调出 运行 
2-输入cmd或者powershell
3-$  cd  example-dir   进入项目文件夹
4-$  code .    // 直接就在这个vscode 打开文件夹
```

>>> 这样，就能简化  很多操作，作为一名程序员，手尽量不要离开键盘！

```s
	一般，我们都是，退出到桌面，然后点击浏览器，输入地址。
	用命令的话：
	$  start  chrome  www.baidu.com

	这样，自动直接就打开了chrome浏览器，并输入了地址 www.baidu.com 
```

```s
命令 
$  mkdir filename1 filename2 filename3  // 用于在同一个目录下创建三个文件名分别为filename1,filename2,filename3的文件夹。

命令
$  mkdir -p filename1/filename2/filename3   // 用于递归的创建三个文件夹，其中文件夹filename3在文件夹filename2中，filename2在filename1中，这里会从左往右先检测文件夹是否存在，不存在会先创建该文件夹。
mkdir命令参数说明：

  -m, --mode=模式，设定权限<模式> (类似 chmod)，而不是 rwxrwxrwx 减 umask
  -p, --parents  可以是一个路径名称。此时若路径中的某些目录尚不存在,加上此选项后,系统将自动建立好那些尚不存在的目录,即一次可以建立多个目录; 
  -v, --verbose  每次创建新目录都显示信息
  --help   显示此帮助信息并退出
  --version  输出版本信息并退出
```
```s
	一般，我们创建文件以及文件夹，都是一个一个文件/文件夹的创建。
	用命令可以批量创建文件夹和文件：
	创建多个文件夹：
	$  mkdir  src  js  css    // 这样会在当前目录创建三个文件夹
	创建文件：
	$  echo >index.html  [hello World] 回车，Ctrl + C  // 在当前文件夹下创建一个index.html文件,中括号[]的意思是里面的内容可以写可不写，后面的参数是，index.html写入一个hello World 文本
```