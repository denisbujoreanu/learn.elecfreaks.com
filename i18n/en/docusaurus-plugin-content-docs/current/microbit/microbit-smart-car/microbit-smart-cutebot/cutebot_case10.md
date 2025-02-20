# Case 10: Car Following with A Fixed Distance

## Purpose

The [Cutebot](https://www.elecfreaks.com/micro-bit-smart-cutebot.html) moves with a fixed distance between the car and your hands.

![](./images/cutebot-case-10-01.png)

## Materials

1 x [Cutebot Kit](https://www.elecfreaks.com/micro-bit-smart-cutebot.html)

1 x Ultrasonic Sensor

## Software Platform

[MicroSoft makecode](https://makecode.microbit.org/#)

## Programming

### Step 1

Click the "Advanced" to see more choices in the MakeCode drawer.

![](./images/cutebot-pk-1.png)

A codebase is required for [Cutebot](https://www.elecfreaks.com/micro-bit-smart-cutebot.html) programming, click “Add Package” at the bottom of the drawer, search `Cutebot` in the dialogue box and download it.

![](./images/cutebot-pk-11.png)

***Note:*** If you met a tip indicating incompatibility of the codebase, you can continue with the tips or build a new project there.

### Step 2

Drag the "set left wheel speed and right wheel speed" into the `On start` brick.

![](./images/case_10_01.png)

### Step 3

Set a `Sonar` variable to  save the detected `Cm` value in the `Forever` brick.

If the detected value is between`5` and `10` , the car stops moving.

If the detected value is below`5` , the car reverses because of the short distance with the hands.

If not any, the car moves forward to catch up with the hands because of the far distance with the hands and then stay still .

![](./images/case_10_02.png)


### Programming

Links: [https://makecode.microbit.org/_YxxfyPVsmHjg](https://makecode.microbit.org/_YxxfyPVsmHjg)

You can also download it directly below:

<div
    style={{
        position: 'relative',
        paddingBottom: '60%',
        overflow: 'hidden',
    }}
>
    <iframe
        src="https://makecode.microbit.org/_YxxfyPVsmHjg"
        frameborder="0"
        sandbox="allow-popups allow-forms allow-scripts allow-same-origin"
        style={{
            position: 'absolute',
            width: '100%',
            height: '100%',
        }}
    />
</div>


## Result

The [Cutebot](https://www.elecfreaks.com/micro-bit-smart-cutebot.html) adjusts itself to keep a fixed distance with your hands.

![](./images/cutebot-case-10.gif)

## Exploration


## FAQ
---

## Relevant Files
---
