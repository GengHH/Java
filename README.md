# 初识Java
Java的基础知识


标签（空格分隔）： Java环境

----------


## 了解Java的各种环境

### JDK （Java Development Kit，Java 开发工具）

   这是JDK，JDK 是整个Java的核心，包括了Java运行环境（jre）、Java工具和Java基础类库。
   **除此之外还分为Java SE 、Java EE 、Java ME**
   
*JDK(Java Development Kit) 是 Java 语言的软件开发工具包(SDK)。*

> SE(J2SE)，standard edition，标准版，是我们通常用的一个版本，
        从JDK5.0开始，改名为Java SE。
        
> EE(J2EE)，enterprise edition，企业版，使用这种JDK开发J2EE应用程序，
         从JDK 5.0开始，改名为Java EE。 
         
>ME(J2ME)，micro edition，主要用于移动设备、嵌入式设备上的java应用程，        
         从JDK 5.0开始，改名为Java ME。

   
### JRE （Java Runtime Environment，Java运行环境）

   运行JAVA程序所必须的环境的集合，包含JVM标准实现及Java核心类库。
JDK 它大于JRE，还包含了用于开发的工具。
有jre这个东西，就能运行java程序。

**举例说明：**
如果说虚拟机是操作系统，jre就是pc硬件。
java之所以能跨平台，就是在jre的层次上屏蔽了不同系统的差异。
jre可以单独下载安装
若下载的是jdk，jre自然也包含在了其中。你能发现你下载安装的jdk，有两个jre。
jdk目录下面的是 io流 等等标准的JDK jar包
还有一个jre文件夹下面是 java用来编译你所写的代码的工具。
  
  
  
