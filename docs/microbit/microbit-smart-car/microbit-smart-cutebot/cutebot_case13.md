---
sidebar_position: 16
sidebar_label: joystick:bit手柄远程控制
---

# 案例13:joystick:bit手柄远程控制

## 目的

使用joystick:bit遥控器的摇杆和按钮完成远程遥控Cutebot。

![](./images/cutebot-case-13-01.png)

## 使用材料

1 x [Cutebot套件](https://item.taobao.com/item.htm?spm=a1z10.3-c-s.w4002-18602834180.23.78b86655ZP5Yg8&id=598365555295)

1 x [Joystick:bit2](https://item.taobao.com/item.htm?spm=a1z10.3-c-s.w4002-18602834180.15.70606655uS6pSx&id=582662338443)


## 软件平台

[微软 makecode](https://makecode.microbit.org/#)

## 编程

### 步骤 1

在MakeCode的代码抽屉中点击高级，查看更多代码选项。

![](./images/cutebot-pk-1.png)

为了给Cutebot套件编程，我们需要添加一个代码库。在代码抽屉底部找到“扩展”，并点击它。这时会弹出一个对话框。搜索`Cutebot`，然后点击下载这个代码库。

![](./images/cutebot-pk-11.png)

为了给Joy:stick手柄编程，我们需要添加一个代码库。在代码抽屉底部找到“扩展”，并点击它。这时会弹出一个对话框。搜索`joystick`，然后点击下载这个代码库。

![](./images/case_13_01.png)

注意：如果你得到一个提示说一些代码库因为不兼容的原因将被删除，你可以根据提示继续操作，或者在项目菜单栏里面新建一个项目。

### 步骤 2: Joystick:bit编程

在`当开机时`积木块中设置无线电组别为`1`；

`X`轴和`Y`轴的数值范围为`0~1023`，当摇杆位置在中心的时候，它的理论值为`512`，故需要将0~1023`map`映射到`-100~100`这个范围之内。

在`无限循环`积木块中设置变量`x`它的值为`X`轴的读值映射到`-100~100`这个范围的值。

在`无限循环`积木块中设置变量`y`它的值为`y`轴的读值映射到`100~-100`这个范围的值。

通过无线发送值将变量`x`和变量`y`发送出去。


![](./images/case_13_02.png)

#### 程序

请参考程序连接：[https://makecode.microbit.org/_cPUgXJRLuCmH](https://makecode.microbit.org/_cPUgXJRLuCmH)

你也可以通过以下网页直接下载程序。

<div
    style={{
        position: 'relative',
        paddingBottom: '60%',
        overflow: 'hidden',
    }}
>
    <iframe
        src="https://makecode.microbit.org/_cPUgXJRLuCmH"
        frameborder="0"
        sandbox="allow-popups allow-forms allow-scripts allow-same-origin"
        style={{
            position: 'absolute',
            width: '100%',
            height: '100%',
        }}
    />
</div>

### 步骤 3: 小车编程

在`当开机时`(开始)积木块中设置无线电组别为`1`，一定要和遥控端设置为同一组别，否则无法匹配。

然后在`当接收到数据`积木块中插入两次判断语句，分别判断无线电接收值`name`是否为`x`或者`y`；

当无线电收到的`name`值为`x`时，为加速度计`X`轴数据，将`value`值保存到`xValue`变量；

当无线电收到的`name`值为`y`时，为加速度计`Y`轴数据，将`value`值保存到`yValue`变量；

在`无限循环`积木块中，设置左轮速度为`yValue`+`xValue`，右轮速度为`yValue`-`xValue`。


![](./images/case_12_02.png)

#### 程序

请参考程序连接：[https://makecode.microbit.org/_CrmVWJCrD2au](https://makecode.microbit.org/_CrmVWJCrD2au)

你也可以通过以下网页直接下载程序。

<div
    style={{
        position: 'relative',
        paddingBottom: '60%',
        overflow: 'hidden',
    }}
>
    <iframe
        src="https://makecode.microbit.org/_CrmVWJCrD2au"
        frameborder="0"
        sandbox="allow-popups allow-forms allow-scripts allow-same-origin"
        style={{
            position: 'absolute',
            width: '100%',
            height: '100%',
        }}
    />
</div>

## 结论

用手柄摇杆可以控制小车前进后退转弯速度等。

![](./images/cutebot-case-13.gif)

## 思考

## 常见问题
---
## 相关阅读
---
