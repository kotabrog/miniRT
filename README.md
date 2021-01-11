# miniRT

<p align="center">
	<img src="https://github.com/kotabrog/miniRT/blob/main/image/miniRT_image.png" width=40%>  <img src="https://github.com/kotabrog/miniRT/blob/main/image/miniRT_image2.png" width=40%>
</p>　

## Overview

I made a simple ray tracing in C.

## Requirement

- Ubuntu 18.04
- Linux

## Usage

```
git clone ...
cd miniRT
make
./miniRT rt_sample/sample.rt
```

You can switch the image (camera) by pressing the 1 to 9 keys or pressing the arrow keys while the image is displayed.  
To stop displaying the image, press the esc key or the cross button

Save as image:

```
./miniRT rt_sample/sample.rt --save
```

## About test

You can easily test the performance of miniRT

```
make
./test.sh
```

When you're done playing, press the esc key to switch to the next sample.

## Features

- I'm using Xlib
- This program can create 5 simple shapes: plane, sphere, cylinder, square and triangles
- This program can set multiple lights
- This program can set multiple cameras to switch the viewpoint. Press the 1 to 9 keys or arrow keys
- If you want to stop displaying the image, press the esc key or the cross button.
- If you want to save the image, specify "--save" in the second argument.

## Reference

- [minilibx-linux](https://github.com/42Paris/minilibx-linux)

## Author

[twitter](https://twitter.com/Kotabrog)

## Licence

[MIT](https://github.com/kotabrog/miniRT/blob/main/LICENSE)
