# install-eclipse-in-ubuntu14.04

Ubuntu14.04下安装eclipse

环境：
Ubuntu 14.04

步骤：
1、安装配置JDK，详见 http://my.oschina.net/u/1407116/blog/227084
2、下载eclipse
从官网http://www.eclipse.org/downloads/下载Eclipse IDE for Java EE Developers的Linux版本
eclipse-SDK-3.7.2-linux-gtk.tar.gz
3、解压
$ tar -zxvf eclipse-SDK-3.7.2-linux-gtk.tar.gz
解压出来是一个eclipse文件夹
4、将文件夹移动到安装目录
$ sudo mv eclipse /usr/local/
5、启动eclipse
$ /usr/local/eclipse/eclipse
6、创建桌面链接
$ sudo su
# gedit /usr/share/applications/eclipse.desktop
写入以下内容
[Desktop Entry]
Name=Eclipse
Comment=Eclipse SDK
Encoding=UTF-8
Exec=/usr/local/eclipse/eclipse
Icon=/usr/local/eclipse/icon.xpm
Terminal=false
Type=Application
Categories=Application;Development;
完成后可以在Application-Programming下看到eclipse图标。

reprinted from:http://my.oschina.net/u/1407116/blog/227087
                  by http://blog.csdn.net/gavin_dinggengjia/article/details/7364375
