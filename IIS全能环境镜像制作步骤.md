## IIS全能环境镜像制作步骤
1. 设置虚拟内存(512M-2048M)和设置任务栏全部底栏显示；

2. 安装chrome；

3. 在服务器管理器--角色中选择添加角色，选择Web服务器(IIS)进行安装；

4. 下载安装PHP Manager for IIS 7，[下载地址:http://www.iis.net/downloads/community/2010/09/php-manager-for-iis-7](http://www.iis.net/downloads/community/2010/09/php-manager-for-iis-7)

5. 下载PHP5.5~PHP7.1(注意vc库问题)，安装到C:\websoft9目录下，[PHP下载地址:https://windows.php.net/download#php-7.0](https://windows.php.net/download#php-7.0)；

6. 修改php.ini参数；

7. 安装MySQL数据库到C:\websoft9目录，并对其进行初始化；

8. 安装phpMyAdmin到C:\websoft9目录，并添加虚拟目录；

9. 安装MySQL-front数据库管理工具；

4. 将默认网站127.0.0.1的目录下原来的文件替换为9panle跳转文件；

5. 上传9panel文件到c:/inetpub/目录下，注意根据镜像的不同选择不同的9panel；

6. 在默认网站添加虚拟目录，检查9panel是否生效；

7. 检查系统更新；

8. 删除浏览器历史记录和日志文件(事件管理器)；

9. 镜像打包。