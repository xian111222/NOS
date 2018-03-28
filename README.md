# NOS
网络操作系统
在Linux下进行C语言编写vi 编译器  ls 显示当前文件夹下的文件 gcc是Linux下的编译器 -E 开关经典程序“Hello,World!”#vi hello.c#include<stdlib.h>#include<stdio.h>void main(){   printf(“hello,world!\r\n”);}GCC编译C源代码的四个步骤1.预处理#gcc-E hello.c-o hello.i作用：将hello.c 预处理输出hello.i文件2.编译#gcc-S hello.i-o hello.s作用：将预处理输出文件hello.i汇编成hello.s文件3.汇编#gcc-c hello.s-o hello.o作用：将汇编输出文件test.s编译输出test.o文件4.链接#gcc hello.o-o hello.exe作用：将编译输出文件hello.o链接成最终可执行文件hello.exe   
