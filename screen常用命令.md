### screen (另一种:Tmux)
#### 安装
`yum install screen`
`rpm -qa|grep screen`

#### 1、创建 screen 终端
`screen`      
 指定作业名称
`screen -S jobname`

#### 2、离开screen终端
Ctrl + a + d

#### 3、显示(list)已创建的screen终端 
`screen -ls`

#### 4、重新连接离开的 screen 终端
`screen -r 2276`  //连接 screen_id(或名称) 为 2276 的 screen终端

#### 5、Screen命令后跟你要执行的程序。
`screen vi test.c`

#### 6、在screen中创建新的screen
Ctrl + a + c

#### 7、关闭或杀死窗口
输入`exit`；
或
Ctrl + a   k

#### 8、清除失效会话
`screen -wipe`
