# 简介

CV32E40P是一个**顺序**（发射、执行）的**四级**流水线**32位**RISC-V处理器。CV32E40P的指令集包含了一部分的自定义扩展指令集，包括有：硬件循环（hardware loops）、地址自增的访存指令（post-increment load and store）以及额外的一系列ALU指令（算术指令扩展、乘累加MAC、向量操作等等）。图1.1为处理器流水线的总体示意图。

![1.1 CV32E40P处理器的总体示意图](https://upic-groupsun.oss-cn-shenzhen.aliyuncs.com/uPic/image-20201202202031191.png)

