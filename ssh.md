``` 
cd ~/.ssh
ls
```
没有id_rsa 和 id_rsa.pub

```
ssh-keygen -t rsa -C "email@address" 
```
一直回车就好

```
ls
```

有id_rsa 和 id_rsa.pub


> gedit id_rsa.pub 然后复制

>> 把id_rsa.pub的内容添加到github账号profile中的SSH key中 

> ssh -T git@github.com 

会提示连接成功

> git config --global user.name 'username'

> git config --global user.email 'email@address'
