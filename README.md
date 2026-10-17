# Micro:bit Flashing Heart Tutorial

## Introduction @unplugged
Welcome! In this tutorial, you will make a heart flash on your micro:bit screen.

## Step 1
Drag a `show icon` block inside the `forever` loop. Choose the **Heart** icon.

```blocks
basic.forever(function () {
    basic.showIcon(IconNames.Heart)
})
```

## Step 2
Now, add a `pause` block right beneath it so the heart stays on the screen for a moment.

```blocks
basic.forever(function () {
    basic.showIcon(IconNames.Heart)
    basic.pause(500)
})
```



> Open this page at [https://lark098.github.io/tuorial-test/](https://lark098.github.io/tuorial-test/)

## Use as Extension

This repository can be added as an **extension** in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **New Project**
* click on **Extensions** under the gearwheel menu
* search for **https://github.com/lark098/tuorial-test** and import

## Edit this project

To edit this repository in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **Import** then click on **Import URL**
* paste **https://github.com/lark098/tuorial-test** and click import

#### Metadata (used for search, rendering)

* for PXT/microbit
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
