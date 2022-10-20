# Densidad de píxeles
Etiquetas: 

## Qué es
**densidad de pantalla = anchura de pantalla (o altura) en píxeles /  anchura de pantalla (o altura) en** **pulgadas.**

>Ver: [[Unidades de medida (px, dp...)#^Pixel]]

![imagen de alta densidad](https://dc722jrlp2zu8.cloudfront.net/media/cache/c4/71/c471e634249ad06e794489820b220b92.webp)
![imagen de baja densidad](https://dc722jrlp2zu8.cloudfront.net/media/cache/66/a4/66a49361ef0db61bf3a6671f20f16bca.webp)

# Up until 2010, a pixel meant a pixel, it was measurable and life was easy.

Before the iPhone 4’s retina display, the number of pixels that could fit on a square area of 1 inch was 163 pixels. It was fixed or at least was the standard.

All that changed when the iPhone introduced retina display. An inch of a retina display could now house 326 pixels. And as it is a convention, other companies started following suit with crazy pixel counts included per inch of screen.

![](https://miro.medium.com/max/1400/1*B0tdSuVaEaw9Wl-FF4LY_g.png)

# Here’s where all the problem started-

Say you designed a button 2 pixels high and 4 pixels wide, the size would now vary hugely depending if your website or app is viewed on a phone screen with 163 pixels per inch or 326 pixels per inch display. You would now have to make the design over and over again every time for a range of devices with the same sizes, let alone different aspect ratios.

![](https://miro.medium.com/max/1400/1*KpsP_Zxkk8Z7SfEPqMOrCA.png)

# Apple solved this problem by introducing the Point (pt)
A point was defined to be exactly equal to a pixel when it was viewed on the original iPhone. i.e 1 px = 1 pt when viewed on a screen of density 163 pixels/inch. As different versions of the iPhone came with different screen resolutions, iOS would then internally convert the points to pixels to make a button look the same size no matter how many pixels fit in an inch of the screen.

>Ver [[Unidades de medida (px, dp...)#^pt]]

## 1 pt = (ppi of your sceen/163) px
A designer could now design a 4 x 2 pt button and they would look the same everywhere.

![](https://miro.medium.com/max/1400/1*-RPvUGYnqmf2g8P8NITQZA.png)

## Recursos
### Enlaces
https://medium.com/hemisphereco/what-is-px-what-is-a-pt-what-is-dp-ecaefefa25a2
https://angrytools.com/android/pixelcalc/