首先打开开始菜单，找到 windows 系统 -- 右击命令提示符 -- 更多 -- 以管理员身份运行

输入以下命令，回车：

sc config i8042prt start= disabled

然后重启电脑，就好啦~

你想恢复的时候，只要重复上面的动作，输入的命令改为：

sc config i8042prt start= auto
