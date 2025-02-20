---
sidebar_position: 9
sidebar_label: 转向示廓灯
---

# 案例06:转向示廓灯

## 目的

大家好！今天我要向大家展示一个很酷的项目，我们将制作一辆Cutebot智能赛车，在转弯时能自动开启转向灯和转向示廓灯！这将使我们的赛车更加安全和引人注目。

想象一下，当我们在道路上驾驶时，转弯时打开转向灯可以提醒其他车辆我们的行驶意图。同时，开启转向示廓灯可以使我们在夜间或低能见度条件下更加可见。今天，我们将学习如何利用条件语句来实现这个功能。

![](./images/cutebot-case-06-01.png)

## 使用材料

1 x [Cutebot套件](https://item.taobao.com/item.htm?spm=a1z10.3-c-s.w4002-18602834180.23.78b86655ZP5Yg8&id=598365555295)

## 软件平台

[微软 makecode](https://makecode.microbit.org/#)

## 编程

### 步骤 1

在MakeCode的代码抽屉中点击高级，查看更多代码选项。

![](./images/cutebot-pk-1.png)

为了给Cutebot套件编程，我们需要添加一个代码库。在代码抽屉底部找到“扩展”，并点击它。这时会弹出一个对话框。搜索`Cutebot`，然后点击下载这个代码库。

![](./images/cutebot-pk-11.png)

注意：如果你得到一个提示说一些代码库因为不兼容的原因将被删除，你可以根据提示继续操作，或者在项目菜单栏里面新建一个项目。

### 步骤 2

在`当开机时`积木块中设置Rainbow LED灯连接口为`P15`，一共有`2`颗LED灯；

`right`右侧灯为从第`1`颗灯开始往后`1`颗灯。

`left`左侧灯为从第`0`颗灯开始往后`1`颗灯。

![](./images/case_06_01.png)

### 步骤 3

在`当按钮A按下时`积木块中插入`循环`积木块，右侧示廓灯显示黄色，右侧LED大灯显示黄色(RGB控制)，延迟500ms后，关闭右侧示廓灯和LED大灯，完成一次闪烁。

![](./images/case_06_02.png)


### 步骤 4

在`当按钮B按下时`积木块中与右侧同理，只不过将右侧改为左侧。

![](./images/case_06_03.png)

### 程序

请参考程序连接：[https://makecode.microbit.org/_aqW6aW5855gR](https://makecode.microbit.org/_aqW6aW5855gR)

你也可以通过以下网页直接下载程序。

<div
    style={{
        position: 'relative',
        paddingBottom: '60%',
        overflow: 'hidden',
    }}
>
    <iframe
        src="https://makecode.microbit.org/_aqW6aW5855gR"
        frameborder="0"
        sandbox="allow-popups allow-forms allow-scripts allow-same-origin"
        style={{
            position: 'absolute',
            width: '100%',
            height: '100%',
        }}
    />
</div>
---

## 结论

当按钮A按下时，右侧LED车灯和示廓灯闪烁5次

当按钮B按下时，左侧LED车灯和示廓灯闪烁5次

![](./images/cutebot-case-06.gif)

## 思考

如何让你的小车按下按钮A开启双闪，按下按钮B关闭双闪呢。



## 常见问题
---
## 相关阅读
---
