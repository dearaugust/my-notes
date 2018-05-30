# git公钥绑定!

- 1.打开后的如下所示，输入指令：
```
    cd ~/.ssh/  
```
如果提示如果提示 “ No such file or directory" 那么可以采用 命令：
```
    mkdir ~/.ssh
```
来创建文件夹

- 2.配置全局的name和email，这里是你的github的账号和email配置的命令如下：
```
git config --global user.name "dearaugust" 

git config --global user.email "419491539@qq.com" 
```

- 3.生成SSH公钥 命令如下：
```
    ssh-keygen -t rsa -C "419491539@qq.com"
```

- 4.查看 '.ssh' 下 'id_rsa.pub' 文件，将文件内容复制到GitHub设置里。