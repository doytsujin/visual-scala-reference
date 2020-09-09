---
title: foldLeft
---

# `foldLeft`

{{< signature >}}

`foldLeft` aplica, de izquierda a derecha, el operador binario `op` a cada elemento y al resultado del anterior `op`.
La primera vez que `op` es aplicado es alimentado con el valor inicial `z`.

{{< figure src="images/functions/foldLeft.svg" >}}

En colecciones vacías, esta función ni siquiera aplica `op` y el valor inicial `z` es devuelto directamente.

{{< figure src="images/functions/foldLeft.2.svg" >}}

