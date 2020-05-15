###建议安装原版BBR Plus 

1、安装BBR加速，指向下面命令 #选择项目#2 
# cd /usr/src && wget -N --no-check-certificate "https://raw.githubusercontent.com/DuoBaoX/Linux-NetSpeed/master/tcp.sh" && chmod +x tcp.sh && ./tcp.sh

2、注意在弹出的安装界面首先选择项目#2，安装BBR-Plus内核,安装过程可能时间较长,耐心等待。

3、安装完成后会提示重启VPS,输入Y，然后回车，确认重启。然后等待几分钟，再使用SSH工具连接vps（连接方法是点软件上打开，找到之前保存的连接，然后点连接）登陆后执行下列命令

# cd /usr/src && ./tcp.sh

4、在弹出安装界面,项目#7,然后回车，使用BBR-Plus加速，等待安装完成提示bbr启动成功即可。
