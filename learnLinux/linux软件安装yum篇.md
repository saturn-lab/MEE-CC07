# Linux下软件安装（10-15分钟）
## 实验环境：云平台
## 实验工具：putty  或其它 远程工具


## 实验步骤：
### 1 用putty登录远程服务器： 地址101.6.160.22，端口：10122，10222，10322......11022
  用户名：vr    密码：vr123456
### 2 安装软件yum方法（以安装http为例）
    sudo yum install httpd
    
 输入密码 vr123456  
软件安装对话， 选择Y
### 3 启动服务  
    sudo systemctl start httpd
    
  查看  浏览器打开  http://101.6.160.22:10180(每个人不同）
### 4 停止服务   
    sudo systemctl stop httpd
    
  查看  浏览器打开  http://101.6.160.22:10180(每个人不同）
### 5 启动服务,关闭服务sudo systemctl start httpd
查看  浏览器打开  http://101.6.160.22:10180(每个人不同）
    sudo systemctl stop httpd
### 6 删除服务  
    sudo yum remove httpd
### 7 验证  启动服务  
    sudo systemctl start httpd  此时报错说明删除成功
