# jump-servers
跳板机登录通用命令
执行命令： jump-server s1         
适用对象：win10（powershell），linux，macOS          
使用方法：     
1. 打开server1/2/3/4文件
2. 修改里面的私钥路径 **~/.ssh/server1.pem** 
3. 修改跳板机登录名 **username**
4. 修改跳板机ip以及端口 **127.0.0.1** ，**2222**
4. 在send的那名命令中，修改私钥对应的密码 **yourpassword**
5. 若秘钥对应无密码，删除expect那行开始的剩余代码
