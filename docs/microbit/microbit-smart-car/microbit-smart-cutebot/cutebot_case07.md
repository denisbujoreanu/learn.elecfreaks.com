---
sidebar_position: 10
sidebar_label: 防跌落小车
---
# 案例07:防跌落小车

## 目的

今天我要向大家介绍一个非常有趣的项目，沿着桌面边缘贴一圈黑色胶纸，小车检测到黑线时会迅速后退，然后换一个方向继续前进。

想象一下，当我们驾驶车辆靠近边缘时，我们会注意到并采取相应的措施，比如减速或转向，以避免跌落。类似地，我们可以通过编程来使Cutebot智能赛车能够自动检测边缘并采取相应的行动。

![](./images/cutebot-case-07-01.png)

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

在`当开机时`积木块中显示一个图标。

![](./images/case_07_01.png)

### 步骤 3

在`无限循环`积木块中插入`if`(判断)积木块，判断巡线模块不是两个都检测到(边缘)黑线时，设置左右轮速度为`20`。

如果不是，设置左右轮速度为`-50`迅速倒车离开桌面边缘，延迟`300ms`，左轮不动，右轮随机一个50~100的速度旋转`100ms`。

然后将左右轮速度设置为`0`，暂停一秒，重新前进。

![](./images/case_07_02.png)

### 程序

请参考程序连接：[https://makecode.microbit.org/_DdY3UhfaR0KW](https://makecode.microbit.org/_DdY3UhfaR0KW)

你也可以通过以下网页直接下载程序。

<div
    style={{
        position: 'relative',
        paddingBottom: '60%',
        overflow: 'hidden',
    }}
>
    <iframe
        src="https://makecode.microbit.org/_DdY3UhfaR0KW"
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

沿着桌面边缘贴一圈黑色胶纸，小车检测到黑线时会迅速后退，然后换一个方向继续前进。

![](./images/cutebot-case-07.gif)

## 思考


## 常见问题

## 相关阅读
