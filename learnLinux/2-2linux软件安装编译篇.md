### 我们以一个流行的小程序来学习编译软件的方法
### 小游戏2048在github的地址为   
    https://github.com/mevdschee/2048.c
### 按照说明执行安装程序，会包错。我们需要做些准备工作：安装wget软件，安装gcc。
    sudo yum install wget
    sudo yum install gcc
### 然后执行2048软件的下载安装执行
    wget https://raw.githubusercontent.com/mevdschee/2048.c/master/2048.c    //下载
    gcc -o 2048 2048.c                            //编译安装
    ./2048                                        //执行
