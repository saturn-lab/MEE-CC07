### 我们以一个流行的小程序来学习编译软件的方法
### 小游戏2048在github的地址为   
    https://github.com/mevdschee/2048.c
### 按照说明执行安装程序，会包错。我们需要做些准备工作：安装wget软件，安装gcc，建立并进入目录。
    sudo yum install wget
    sudo yum install gcc
    mkdir game1
    cd game1
### 然后执行2048软件的下载安装执行
    wget https://raw.githubusercontent.com/mevdschee/2048.c/master/2048.c    //下载
    gcc -o 2048 2048.c                            //编译安装
    ./2048                                        //执行

### gcc
### gcc 是GNU编译器套件，是Linux下默认的C/C++编译器.在windows环境下可以通过MinGw等GNU for Windows类工具使用gcc编译套件

### gcc最简单的编译命令如下

gcc -c hello.c -ohello

### gcc -c 后可跟多个输入源文件，最终输出的可执行文件以-o表示.
### -o后紧着希望生成的可执行文件的名称。
### -c 选项表示只编译源文件，而不进行链接，所以对于链接中的错误是无法发现的
### 如果不使用-c选项则仅仅生成一个可执行文件，没有目标文件。更常用的编译方式是make cmake
### make
### cmake
