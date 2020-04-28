###　实验环境 ：云主机
### 实验工具：putty等远程登录工具
### 软件获取：
#### 1 用wget 从互联网获取
#### 2 用scp从局域网服务器获取，从10.0.1.17服务器拷贝xampp724.run这个文件
    scp vr@10.0.1.17:/home/vr/xampp724.run .   
  注意这个步骤需要输入sudo密码vr123456，还需要输入远程服务器密码：Vr123456,2个不一样。
### 软件的安装，先改权限，赋予可执行权限
    chmod -R 777 xampp724.run   
    sudo ./xampp724.run   

XAMPP Developer Files [Y/n] : Y

然后根据提示安装软件。
Setup has finished installing XAMPP on your computer.
出现以上显示，说明安装正确。
### 查看和验证    浏览器打开 http://101.6.160.22:10180(每个人不同） 
停止、启动web服务
首先进入软件安装目录，一般是 /opt/lampp ,命令为
    cd /opt/lampp
    ./ctlscript.sh stop  //停止， 启动为start ，重启为restart 
