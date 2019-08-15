root下

    adduser 用户名  (useradd没有在home下生成文件夹)
    
    passwd 用户名 (设置登录时的密码，忘记密码可以在root下重新设置)
    
    userdel -r 用户名 (删除用户，和用户的文件夹)


vim /etc/shadow 可以看到用户名

ssh 用户名@ip
