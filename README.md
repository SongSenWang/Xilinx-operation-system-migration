# Xilinx-operation-system-migration
# 采用Xilinx公司的Nexys 4DDR开发板进行FreeRTOS操作系统的移植以及小型应用程序的编写

如题。
本项目开发平台采用了Vivado 2018.2版本，若版本不匹配，可能项目在导入时会出现问题；
主要采用了MicroBlaze软核在Vivado以及SDK平台下联合编程，进行操作系统的移植与小型应用的编写，应用程序旨在证明操作系统移植成功；

这里推荐一些比较有用的MicroBlaze开发的链接：
1.http://www.digilent.com.cn/community/567.html  迪芝伦社区关于Arty A7板子使用MicroBlaze的教程，虽然板子不同，但同样适用于N4板子，操作讲解完整详细，可以完成硬软件工程的创建和简单应用的编写；
2.https://www.uisrc.com/portal.php?mod=list&catid=59&page=1 也有关于MicroBlaze操作的讲解，可以借鉴；

项目包含本人实现过程的思路及基本流程的文档，以及Vivado下完整编译过的LED和DDR2应用程序项目2个以及FreeRTOS的教程一份。

