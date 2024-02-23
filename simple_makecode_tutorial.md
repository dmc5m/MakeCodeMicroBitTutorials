
# Simple MakeCode Tutorial

## Introduction
Welcome to this simple MakeCode tutorial. This tutorial will guide you through creating a blinking LED on the micro:bit.

## Step 1: Show LED
Drag an ``||basic:show leds||`` block into the workspace and draw a simple pattern.

```blocks
basic.showLeds(`
    . # . # .
    # . . . #
    . . # . .
    # . . . #
    . # . # .
    `)
```

## Step 2: Blink
Now, let's make it blink. Add a ``||basic:clear screen||`` block and a ``||basic:pause||`` block to create a blinking effect.

```blocks
basic.forever(function () {
    basic.showLeds(`
        . # . # .
        # . . . #
        . . # . .
        # . . . #
        . # . # .
        `)
    basic.pause(1000)
    basic.clearScreen()
    basic.pause(1000)
})
```

## Conclusion
Congratulations! You've just created a program that makes an LED blink on your micro:bit.

