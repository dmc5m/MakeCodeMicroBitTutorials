
# Simple Blink Tutorial

## Step 0 @showdialog
Welcome to the simple blink tutorial!

## Step 1
Drag the ``||basic:show leds||`` block into the coding area.

```blocks
basic.showLeds(\`
    . . . . .
    . # . # .
    . . . . .
    . # . # .
    . . . . .
    \`)
```

## Step 2
Now, let's make it blink. Add a ``||basic:clear screen||`` block, then a ``||basic:pause||`` block. Set the pause to 500 milliseconds.

```blocks
basic.forever(function () {
    basic.showLeds(\`
        . . . . .
        . # . # .
        . . . . .
        . # . # .
        . . . . .
        \`)
    basic.pause(500)
    basic.clearScreen()
    basic.pause(500)
})
```
