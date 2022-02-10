# Unidades de medida
Etiquetas: #UI #medir 

># Up until 2010, a pixel meant a pixel, it was measurable and life was easy.

Before the iPhone 4’s retina display, the number of pixels that could fit on a square area of 1 inch was 163 pixels. It was fixed or at least was the standard.

All that changed when the iPhone introduced retina display. An inch of a retina display could now house 326 pixels. And as it is a convention, other companies started following suit with crazy pixel counts included per inch of screen.

![](https://miro.medium.com/max/1400/1*B0tdSuVaEaw9Wl-FF4LY_g.png)

## Píxel (px)
^Pixel
Un píxel es un **punto que emite un solo color en una imagen o en una pantalla**. ^6cfb7e

>Ver también [[Densidad de píxeles]]

### Píxel lógico
What we talked about so far was about physical pixels. This is not to be mistaken with the CSS pixel (logical pixel) used by websites or the px measure you use on Figma.
Similar to the definition of pt and dp, a CSS pixel (logical pixel) is exactly equal to a physical pixel when viewed on a screen with 96 pixels/inch, at an arm’s length.

## dp (pixeles de densidad independiente)
Son **unidades flexibles** que se escalan a dimensiones uniformes en cualquier pantalla.

Cuando desarrolle aplicaciones para Android, utilice dp para mostrar los elementos uniformemente en pantallas con diferentes densidades.

Un **dp es igual a un pixel en una pantalla de densidad de 160**ppp. 

Para calcular dp:

**dp = (ancho en píxeles * 160) / densidad de la pantalla.**

[[Unidades de medida (px, dp...)#^Pixel]], [[Densidad de píxeles]]

## sp (píxeles de escala independiente)
Scale-independent-Pixels en inglés, tienen la misma función que los función que los **dp** , la diferencia es que se aplican a textos, en el caso de Android para **TextView** o cualquier otro elemento que soporte una fuente.

El valor por defecto de un **sp** es el mismo que el valor por defecto de un **dp**. Por ejemplo:

```
TextView
android:id="@+id/textView"
android:text="Tamaño de texto 25sp (Scale-independent-Pixels)"
android:layout_width="match_parent"
android:layout_height="wrap_content"
android:textSize="25sp"
```

![Densidad de pixeles](https://dc722jrlp2zu8.cloudfront.net/media/cache/05/70/0570a07a9db969d8a365bd72adb3d94d.webp)

**La diferencia principal entre un sp y un dp es que el sp preserva los ajustes del usuario respecto a la fuente ** . Los usuarios que tengan ajustes para agrandar el texto verán que el tamaño del texto concuerda con sus preferencias. Por ello, se recomienda el uso de esta unidad de medida para fuentes.


## Punto (pt)
^6c5a83

1 pt = (ppi of your sceen/163) px

## Recursos
### Enlaces
- https://openwebinars.net/blog/diferencias-entre-px-dp-y-sp-en-android/
- https://medium.com/hemisphereco/what-is-px-what-is-a-pt-what-is-dp-ecaefefa25a2
- https://pixplicity.com/dp-px-converter
- https://angrytools.com/android/pixelcalc/