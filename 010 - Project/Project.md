[TOC]

# 计组课设

## 部件级实验

### 实验一

### 实验二

### 实验三

参考[文章](https://blog.csdn.net/weixin_46841376/article/details/115540172)

#### 微指令格式

- uIR23-uIR16：A7~A0
- uIR15~uIR12：S3、S2、S1、S0
- uIR11：M
- uIR10~uIR8：0
- uIR7~uIR1：CPR0、CPR1、CPR2、LM、DM、RM、C0
- uIR0：0

#### 实验总结

1. 如果芯片选择错误，会导致传输电路图给硬件时一直卡在0%，而且一旦更换芯片就会导致所有的引脚要重新设置。
2. 写ROM时，分为地址和数据，地址只用写起始地址就可以，之后每条指令（数据）用逗号分割，最后加上分号。所有的指令都是十六进制、地址还不清楚。
3. 传入指令时，首先要连接串口，然后点写入ROM。
4. 模256计数器，需要预设位全为1，才能从0开始一点点的计数。
5. ALU的C0，要用0时，要传送1；要用1时，传送0（PPT中写的）
6. ALU中的控制位表中，汉字"加"为真正的加法，"+"为或运算。

### 实验四

## 整机实验

## 参考资料 ^__ ^

源代码：https://github.com/jxyjason/Prototype-with-Quartus

B站超详细视频讲解：[hhztt](https://space.bilibili.com/506973721/channel/seriesdetail?sid=3453953)

CSDN学长：[叶卡捷琳堡](https://blog.csdn.net/weixin_46841376)

