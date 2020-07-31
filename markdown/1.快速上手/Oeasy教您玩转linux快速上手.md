```java
java
```

# 快速入手

## 图形与终端

### Linux是什么

#### Linux的分布

#### 怎么读

### linux终端

#### 打开终端

##### 双击xfce

##### 在指定文件夹右键

##### 所有应用程序,终端模拟器

##### 切换界面

#### 新建终端

##### 新建终端选项卡快捷键

##### 分离选项卡

##### 在选项卡之间跳转

#### 用终端打开终端? 

找到对应命令

找到文件位置

#### 为终端设置快捷键

##### Ctrl+T

### 我在哪

#### pwd

##### 直接运行pwd

##### 在图形界面找到位置

##### 路径的表示

###### 把路径从gui直接拖动到terminal

###### 把路径从terminal复制粘贴到地址栏

##### ls 看看当前位置都有什么

##### clear进行清屏操作 ctrl+c

##### 总结三板斧、互相找路径

### 终端的控制

##### 上一条命令 下一条命令方向键

##### 复制一部分命令,粘贴一部分命令

### 灵魂之问whatis 

#### 命令是动词 参数是宾语 选项是开关 

#### whatis pwd

#### whatis clear

#### whatis whatis

### Man=manual

#### Man pwd

#### Man ls

#### Man man

##### 快捷键

###### F forward

###### B backward

###### Up 

###### Down

###### Q退出

##### Pwd –help不能用,找到他

### whereis在哪?

#### Whatis pwd

#### Whereis pwd

#### 找到文件夹具体位置

#### 使用绝对路径执行

#### Whereis clear

#### Whereis whatis

#### Whereis whereis

#### 灵魂第二问

#### 发现有两个以上的地址,怎么办,哪个是?

### which哪个?

#### 灵魂之问whatis clear

#### 灵魂二问whereis clear

#### 灵魂三问 which clear

#### Whatis which

#### Whereis which

#### Which which

#### 内建命令

#### https://en.wikipedia.org/wiki/Shell_builtin

#### Which pwd

#### Which /bin/pwd这个就是一个存储于硬盘的外部命令

#### Pwd –help

#### /bin/pwd –help

#### 思考

##### 如果我把这个pwd删除了会怎么样

##### pwd 还能运行么?

##### 硬盘文件删除了 pwd还能运行么

### Type

#### Type直接回车

#### 试试各种东西的type

##### Type pwd

##### Type man

##### Type clear

##### Type oeasy

#### 对type灵魂三问

##### Whatis

##### Where

##### which

#### 使用type去反问

##### Type whatis

##### Type whereis

##### Type which

##### Type type

#### 查看type文档

##### Man type但是找不到

##### 搜索找到页面

###### https://en.wikipedia.org/wiki/Type_(Unix)但是没有细节

###### https://www.gnu.org/software/bash/manual/html_node/Bash-Builtins.html有细节

##### 先试试

###### \-t

###### Type -t whatis

###### Type -t whereis

###### Type -t which

###### Type -t /bin/pwd

###### \-a

###### 三问灵魂

###### \-p

###### \-P

## 终端应用实例

### Yes命令作用不断输出y

#### Man yes观察选项和参数

##### 参数

###### Yes oeasy

##### 选项

###### Man --help

###### Man –version

##### 回头看

###### 回头看man ls(ls是man的参数还是选项)

###### Ls -a是参数还是选项

###### Man pwd是什么 

### Alias

#### alias y=yes

#### y oeasy

#### alias yo=yes oeasy

#### man alias

#### alias

##### ll

##### la

##### lsa

三种命令的总结可执行的程序,内建命令,别名

可以用which来进行区分

Type ls

### Factor命令

#### Man factor

#### 选项

##### Factor –help

##### Factor –version

#### 参数

##### Factor 200

##### Factor 大小写是否影响

##### Factor 20000000000000000000000

##### Factor 0

##### Factor 0.111

##### Factor abc

##### Alias factor = fa

## 终端应用管理

### Apt-get

#### 如何安装应用

##### 先搜索

##### Man Apt-get

##### 尝试update,不允许

### 新命令sudo

#### 先三问再type

#### Apt-get更新 update

###### sudo 这个时候注意方向键控制光标,ctrl+a到终端开始位置,ctrl+e到终端结尾位置

###### 升级man命令

###### 先三问

###### Man --version

###### apt-get upgrade man 

###### man –version

### linuxlogo

#### 三问

#### 观察所在位置

#### man显示

#### 这就是新安装的软件 

### apt-get remove

##### 发现提示当中有可以remove的程序

##### 试试remove删除应用的方法 remove一个

#### Autoremove的方式

#### 继续观察man apt-get

##### Ls /etc/apt/sources.list

### Cat

#### Cat /etc/apt/sources.list

#### 找到地址,用火狐访问

### more

### less

### 修改文本gedit

#### 新建文档

#### 灵魂三问

#### man

#### 修改 用浏览器 source.list拖过来

#### 然后改乱

#### 观察apt-get update

### 换源

#### 搜apt-get换源

#### https://mirrors.tuna.tsinghua.edu.cn/help/ubuntu

#### 控制版本

#### 修正list文件

#### 换源成功

#### 还能装什么应用

### 文字处理Figlet

##### 直接运行 写文字Oeasy

##### 三问

##### Man

##### https://aotu.io/notes/2016/11/22/figlet/index.html

### toilet

#### 安装

##### 随时三问

##### Man

#### Toilet

##### 直接运行,写文字oeasy

##### Man 观察

### 火焰动态图形

####  Aafire

##### 安装

##### 三问

##### 都有些什么

### Sl

#### Apt-get install sl

#### Man sl

#### 恶作剧Alias ls=sl

#### 这个东西装在哪里了?

#### 灵魂三问

### 水族馆

asciiquarium

### apt-cache

#### man apt-get

#### apt之后按tab观察提示

#### apt-cache search matrix

### CMatrix

#### 安装

#### 手册

#### 玩耍

#### Whereis …

#### 在服务器什么位置

#### apt-cache showsrc cmatrix

### Cowsay

#### 先安装

#### 然后man

#### 然后说句话

#### Cowsay -l

#### Alias dunkeysay=

### 中文输入法fcitx

#### 打开输入法

#### 直接运行sogou

#### 切换输入法

#### 重启环境

#### 观察输入法

#### 找到输入法

#### 更新输入法

#### 右键快捷方式观察应用名称,然后直接在terminal跑

#### 也可以输入中文

#### 观察terminal的编码格式,修改一下观察在运行apt-get会有乱码出现 

### 管道pipe\|

#### Cowsay ls

#### Ls\|cowsay

##### Pwd

###### Pwd」cowsay

###### Pwd\|toilet

###### Pwd\|toilet\|cowsay

##### 本来应该输出到屏幕标准输出的字节流,通过管道流到了某一个命令那里

###### Ls\|donkeysay

###### Ls \| figlet 

###### Ls \|more

###### ls \|less

###### Ls\|figlet\|cowsay

### Fortune

#### 下载

#### 文档

#### 运行

█ **fortune ascii-art** ▐▌

#### 管道

#### 两边分别带参数

**fortune \| cowsay -f duck **

### 其他fortune

#### Apt-cache search fortune

#### 安装zh

#### 然后让牛说中文

#### 然后让狐狸说中文火狐

### 应用管理aptitude

#### Aptitude

#### 安装运行 

#### 观察

## 桌面应用举例

### 桌宠Oneko

### 新建终端、新建终端页

#### 终端所在位置

### Xeyes

##### 安装使用

##### 观察参数

### 运行火狐

#### 直接运行

#### Man firefox

#### Firefox参数细节

##### Firefox shiyanlou.com

##### 结束进程

##### Firefox -h

##### Firefox -v

##### Firefox –search 123

### nautilus

#### 从终端开启文件夹

#### Apt-get update

#### Apt-get install nautilus

### 这个文件装在哪里了?

#### 找到这个文件

#### 我可以在这个gui的地方打开终端

#### 然后在这个终端直接打开这个nautilus就是当前位置了

#### 文件夹的相互拖动

#### 文件的相互拖动 

#### 拖动来

#### 我如果在别的位置也想直接打开怎么办?nautilus加上绝对地址,就打开了 
