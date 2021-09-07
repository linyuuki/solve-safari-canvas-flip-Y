# solve-safari-canvas-flip-Y
Y flip problem that may occur when acquiring safari canvas images

When using toDataURL() to copy an image from the canvas of pixi.js, the y flip phenomenon will appear on the safari browser. 
However, everything works fine on Google Chrome on PC.

[issues](https://github.com/pixijs/pixijs/issues/2283)

I noticed [jpweeks](https://github.com/pixijs/pixijs/issues/2283#issuecomment-234364447) mentioned keyword, but no solution is given. 

When using pixi.js, specify the canvas and context.
Set premultipliedAlpha to True to solve this problem.

When using safari to view this index.html, everything is as you wish.

use safari to check this [demo](https://linyuuki.github.io/solve-safari-canvas-flip-Y/)

Hope it can help you.

