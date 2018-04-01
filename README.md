# jump-servers
跳板机登录是间麻烦的事情，特别是跳板机又特别多，私钥又要输密码。一般人还要打开一些如CRT之类的软件，甚至麻烦。现在只要一个命令即可解决所有烦恼         
执行命令： jump-server s1         
适用对象：win10（powershell），linux，macOS          
使用方法：     
1. 打开server1/2/3/4文件
2. 修改里面的私钥路径 **~/.ssh/server1.pem** 
3. 修改跳板机登录名 **username**
4. 修改跳板机ip以及端口 **127.0.0.1** ，**2222**
4. 在send的那名命令中，修改私钥对应的密码 **yourpassword**
5. 若秘钥对应无密码，删除expect那行开始的剩余代码
