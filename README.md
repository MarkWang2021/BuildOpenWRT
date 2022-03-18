# BuildOpenWRT
Build OpenWRT Fireware use Lede Repository

1、使用了lede的源代码

2、缺省ip地址：192.168.1.1  缺省密码：password

3、设定每周自动编译，x64每周4、x32每周5

4、保存selected luci app内容到luci-app.buildinfo,保存.config 文件到fullconfig.buildinfo

5、mini版本仅包含passwall和zerotier app，全版本包括了常用的内网穿透、vpn服务、管理软件等

6、mini版本包含默认的passwall配置文件

7、为方便使用，x64 mini设置默认ip 10.70.228.225，x32 mini设置默认ip 192.168.1.5
