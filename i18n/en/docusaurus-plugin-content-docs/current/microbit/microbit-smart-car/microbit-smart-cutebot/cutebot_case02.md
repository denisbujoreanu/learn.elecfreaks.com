# Case 02: Speed Up Gradually

## Purpose

In case 01, we can find the  [Cutebot](https://www.elecfreaks.com/micro-bit-smart-cutebot.html) moves too fast to go steadily(the universal wheel goes off the ground) at the beginning.

We will learn to gradually speed up the car for a steady move at the beginning in this case.

![](./images/cutebot-case-02-01.png)

## Materials

1 x [Cutebot Kit](https://www.elecfreaks.com/micro-bit-smart-cutebot.html)

## Software Platform

[MicroSoft makecode](https://makecode.microbit.org/#)

## Programming

### Step 1

Click the "Advanced" to see more choices in the MakeCode drawer.

![](./images/cutebot-pk-1.png)

A codebase is required for  [Cutebot](https://www.elecfreaks.com/micro-bit-smart-cutebot.html) programming, click “Add Package” at the bottom of the drawer, search `Cutebot` in the dialogue box and download it.

![](./images/cutebot-pk-11.png)

***Note:*** If you met a tip indicating incompatibility of the codebase, you can continue with the tips or build a new project there.

### Step 2

Choose "show icon" in the `On start`brick.

Set the `speed` variable to 0 which means the on start speed is 0.

![](./images/case_02_01.png)

### Step 3

Drag setting speed bricks for left and right wheel and set the value as `speed` in "forever" brick, then add one to `speed`.
If `speed` is `100` which is the maximum speed, set `speed` to 0 and restart it.

![](./images/case_02_02.png)

### Programming

Links: [https://makecode.microbit.org/_Au3Ji6KF0H6E](https://makecode.microbit.org/_Au3Ji6KF0H6E)

You can also download it directly below:

<div
    style={{
        position: 'relative',
        paddingBottom: '60%',
        overflow: 'hidden',
    }}
>
    <iframe
        src="https://makecode.microbit.org/_Au3Ji6KF0H6E"
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

The  [Cutebot](https://www.elecfreaks.com/micro-bit-smart-cutebot.html) speeds up gradually and the universal wheel will not go off the ground due to the high speed.

![](./images/cutebot-case-02.gif)

## Exploration

How to program to make the car speed up gradually and then speed down gradually?

## FAQ
---
## Relevant Files
---
