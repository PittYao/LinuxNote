1. 连网安装,解决依赖性.类似Maven
2. yum源在 /etc/yum.re 配置远程仓库url地址
	默认Base中配置的有url地址,可用国内镜像url替换
3. 光盘搭建本地yum源仓库
	1. 是网络yum url失效
		将base文件夹 mv 为 .bak
	2. 挂载 光盘 mount /dev/sr0 /mnt/cdrom
	3. 修改 media 配置远程仓库url地址为 挂载点
		修改baseUrl 为 /mnt/cdrom   enable=1 
	