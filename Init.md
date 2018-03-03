# Init
/etc/init.d contains a list of scripts that are executed by init process during startup and shutdown. 
To automatically run a particular program or script at startup, you can create a corresponding init.d script.

A typical init.d script gets executed with arguments such as "start", "stop", "restart", "pause", etc.

建立脚本
> $ sudo vim /etc/init.d/autorun

修改权限
> $ sudo chmod 755 /etc/init.d/autorun

添加默认运行等级
> $ sudo update-rc.d autorun defaults

remove the init.d script from start-up service list
> $ sudo update-rc.d -f autorun remove
