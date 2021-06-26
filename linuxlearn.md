# Linux manjaro KDE发行版学习

# 安装与配置

## 制作启动盘

### 工具
> + Rufus:前往*[Rufus官网](https://rufus.ie/zh/)*下载
> + 镜像：前往：https://manjaro.org.cn/ 下载
## 1、内建命令  


内建命令实际上是shell程序的一部分，包含一些比较简单的linux系统命令，这些命令写在bash源码的builtins里面，由shell程序识别并在shell程序内部完成运行，通常在linux系统加载是shell就被加载并驻留在系统内部中。而且解析内部命令shell不需要创建子进程，因此其执行速度比外部命令快。  
    

## 2、外部命令

外部命令是linux系统中的实用程序部分，因为实用程序的功能通常都比较强大，因此其包含的程序量也会很大，在系统中加载时并不随系统一起被加载到内存中，而是在需要时才将其调入内存。虽然其不包含在shell中，但是其命令执行过程是由shell程序控制的。外部命令是在Bash之外额外安装的，通常放在/bin，/usr/bin，/sbin，/usr/sbin等等。  
    

##### type XXX 可以区分内建和外部命令

## 3、帮助命令

help，man，info。（info如果没有可以自行安装）
