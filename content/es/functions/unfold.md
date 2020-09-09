---
title: unfold
---

# `unfold`

{{< signature >}}

`unfold` crea una colección tomando cada par de valores devueltos por la función `f` tanto para obtener el elemento actual como para calcular el siguiente, mientras que la función los devuelva envueltos con `Some`.

Deja de construir la colección tan pronto como `f` devuelva `None`.

La primera vez que `f` es aplicada es alimentada con el valor inicial `s`.

{{< figure src="images/functions/unfold.svg" >}}
