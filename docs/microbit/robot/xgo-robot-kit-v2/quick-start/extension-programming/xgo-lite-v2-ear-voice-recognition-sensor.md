---
sidebar_position: 4
sidebar_label: XGO-lite V2耳朵-语音识别传感器
---

# XGO-lite V2耳朵-语音识别传感器

## 简介

从前面的介绍中，您应该了解到 XGO Adapter 扩展板板载有 GPIO 和 IIC 接口，可以很方便的扩展传感器，比如 Octopus 系列传感器或者PlantX系列传感器。

本教程我们将使用 Octopus 系列传感器中的语音识别传感器与 XGO-lite 2 联合使用，通过语音来控制XGO-lite V2的运动。那我们开始吧。

## 材料准备

1 × micro:bit XGO Robot Kit V2

1 × Octopus 语音识别电子积木

1 × 4pin杜邦线

透明胶

剪刀

螺丝刀

## 硬件连接

1. 首先需要将XGO Adapter扩展板的两颗螺丝用螺丝刀拧下来，将4pin杜邦线线按下图所示穿过机械臂最下端后插入 IIC(G V 19 20) 接口排针处（注意连接线顺序）。如下图所示：

![](./../../images/microbit-xgo-lite-v2-voice-01.png)

2. 将XGO Adapter扩展板使用螺丝重新固定到XGO-lite V2 头部位置。将Octopus系列的语音识别传感器底部贴上透明胶，并与4pin杜邦线连接，并固定到XGO-lite V2 机身上。(注意XGO Adapter扩展板安装XGO-lite V2头部位置的下方两个螺丝定位孔)

![](./../../images/microbit-xgo-lite-v2-voice-04.png)

![](./../../images/microbit-xgo-lite-v2-voice-02.png)

## 开始编程

本教程将通过图形化编程平台：MakeCode 对两款设备进行编程。请打开makecode平台官网链接：[MakeCode](https://makecode.microbit.org/#). 并按下面操作方式进行编程环境准备。

![](./../../images/microbit-xgo-lite-v2-makecode-01.png)

### 编程环境准备

1.  点击**新建项目**，给项目命名并**创建**

![](./../../images/microbit-xgo-lite-v2-makecode-02.png)



2. 点击**扩展**并在搜索栏搜索**XGO**，选择XGO库，即可将XGO库加载到makecode平台编程环境



![](./../../images/microbit-xgo-lite-v2-makecode-03.png)

![](./../../images/microbit-xgo-lite-v2-makecode-03-1.png)

3. 点击**扩展**并在搜索栏搜索，选择"[https://github.com/elecfreaks/pxt-ASR](https://github.com/elecfreaks/pxt-ASR)"，下载语音识别电子积木的代码库。

![](./../../images/microbit-xgo-lite-v2-voice-03.png)

### 编程示例

![](./../../images/microbit-xgo-lite-v2-voice-05.png)



编程示例程序链接：https://makecode.microbit.org/_e0YKKbMAAd3p

## 演示

![](./../../images/microbit-xgo-lite-v2-voice-06.gif)
