#### 知识点：Linux桌面系统及其配置
练习：
#### Linux系统的基本操作：
#### 1. 使用基本命令实际操作CentOs系统的登陆、退出、重启。
登录：
退出：exit , ctrl+D , logout
重启：halt -p , shutdown -h <time> , poweroff
reboot 命令 , shutdown -r <time> 命令 reset , 组合键 Ctrl+Alt+Del（只适用于控制台下，X Window下无效）
关机：halt -p , shutdown -h <time> , poweroff

#### 2、 在所用的Linux操作系统上，根目录含有哪些内容，各自的功能是什么？
+ /bin：bin是Binary的缩写。这个目录存放着普通用户经常使用的命令文件。
+ /sbin：s就是Super User的意思。这里存放的是系统管理员使用的系统管理程序。
+ /boot：这里存放的是启动Linux时使用的一些核心文件，包括内核、一些链接文件以及镜像文件。
+ /dev：dev是Device(设备)的缩写。该目录下存放的是设备文件，在Linux中访问外部设备的方式和访问文件的方式是相同的。
+ /proc：这个目录是一个虚拟的目录，它是系统内存的映射。我们可以通过直接访问这个目录来获取系统信息。
+ /etc：这个目录用来存放所有的系统管理所需要的配置文件和子目录。
+ /lib：这个目录里存放着系统最基本的动态链接共享库，其作用类似于Windows里的DLL文件。几乎所有的应用程序都需要用到这些共享库。
+ /lost+found：这个目录一般情况下是空的，当系统非法关机后，这里就存放了一些文件。
+ /mnt

在这里面有几个目录，系统提供这些目录是为了让用户临时挂载别的文件系统，我们可以将光驱挂载在/mnt/cdrom上，然后进入该目录就可以查看光驱里的内容了。
    • /root：该目录为系统管理员（即超级用户root）的用户主目录。
    • /home：用以存放普通用户的主目录。在Linux中，每个用户都有一个自己的目录，一般以用户的账号命名。/home/stu
    • /var：这个目录中存放着在不断更新的东西，我们习惯将那些经常被修改的目录放在这个目录下。包括各种缓冲区和日志文件。
    • /tmp：这个目录是用来存放一些临时文件的。
    • /usr：我们要用到的很多应用程序和文件几乎都存放在usr目录下。如：/usr/local：这是提供给一般用户的/usr目录，在这里安装一般的应用软件。
