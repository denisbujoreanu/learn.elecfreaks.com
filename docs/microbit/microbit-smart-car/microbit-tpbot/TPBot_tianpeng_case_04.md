---
sidebar_position: 11
sidebar_label: 避障行驶
---

# 案例04：避障行驶

## 目的
---
- 通过编程让天蓬智能车行驶时可以避开障碍物。

## 使用材料
---

- [天蓬智能车（淘宝购买链接）](https://item.taobao.com/item.htm?ft=t&id=627045784239)



![](./images/TPBot_tianpeng_case_01_01.png)





## 软件
---
[微软makecode](https://makecode.microbit.org/#)


## 编程
---


- 在MakeCode的代码抽屉中点击`高级`，查看更多代码选项。

![](./images/TPBot_tianpeng_case_01_02.png)

- 为了给天蓬智能车编程，我们需要添加一个扩展库。在代码抽屉底部找到`扩展`，并点击它。这时会弹出一个对话框，搜索`tpbot`，然后点击下载这个代码库。

![](./images/TPBot_tianpeng_case_01_03.png)

##示例程序
- `当开机时`micro:bit的LED矩阵显示三角形图案，设置天蓬智能车以`50%`的速度前进，设置车头灯的颜色为`绿色`。
- 在`无限循环`中，将超声波检测到车体与前方障碍物的距离存入变量i中。判断`i<15`和`i≠0`两个条件是否同时为真。如果两个条件同时为真，则天蓬智能车`立即停车`，然后车头灯颜色闪烁三次，再以`30%`的速度后退`1`秒，以`30%`的速度左转`0.5`秒，最后设置车头灯颜色为`绿色`，天蓬智能车继续以`50%`的速度向前行驶。

![](./images/TPBot_tianpeng_case_04_04.png)

### 程序
- 请参考程序连接：[https://makecode.microbit.org/_fddTCuTFc7eE](https://makecode.microbit.org/_fddTCuTFc7eE)

- 你也可以通过以下网页直接下载程序。

<div
    style={{
        position: 'relative',
        paddingBottom: '60%',
        overflow: 'hidden',
    }}
>
    <iframe
        src="https://makecode.microbit.org/_fddTCuTFc7eE"
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
---

- 开机天蓬智能车向前行驶，当遇到障碍物时，立即停车，车头灯闪烁三次后显示红色车灯，然后后退与障碍物保持距离，再左转绕开障碍物车灯亮绿色继续前进。


## 思考
---


## 常见问题
---
Q:使用案例中的代码发现小车不能正常运行？
A:电池电量不足，增大程序中的小车速度参数的数值，并测试。

## 相关阅读
---
