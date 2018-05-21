1. 查询 <br/>
  - yum list &nbsp; 查询可以安装那些yum
  - yum search 关键字  查询源仓库中可以安装的指定正则的yum
2. 安装 <br/>
  - yum -y install 包名   eg: yum -y install httpd-devel
  - 自动解决包的依赖性
3. 升级(尽量不升级)
  - yum -y update 包名  &nbsp; 注意:yum源中必须有版本更高的包
  - 不写包名 更新所有内容 会导致linux崩溃
4. 卸载(尽量不用)
  - yum -y remove 包名
  - 卸载包 会有依赖性  可能导致其他程序崩溃
5. 查询语言组
  - yum grouplist
  - yum grouplinstall 英文软件组名
  - yum groupremove   英文软件组名
6. LANG=en_us 临时将显示语言切换为英文
