---
date: 2016-03-08T21:07:13+01:00
title: "Requisitos técnicos previos al inicio del curso"
weight: 0
description: "Presentación del curso sobre Investigación Reproducible"
---

## Equipo

Creemos conveniente que cada uno de los alumnos se traiga su propio ordenador portátil al curso, de forma que cada alumno termine el curso con el software instalado que resulta necesario para poner en marcha cada una de las partes tratadas en él. De hecho, pensamos que ese es un activo del curso y por eso animamos a traer un portátil propio.

En cualquier caso, y para quien tuviera problemas para desplazarse con el ordenador o no dispusiera de uno, desde la organización podremos proporcionar uno por alumno. La persona interesada solo habría de decírnoslo a lo largo de la semana previa al inicio del curso.

## Software necesario

Con la intención de maximizar el tiempo útil del curso, creemos necesario que los alumnos instalen los siguientes programas de software (todos ellos disponibles en Linux, Mac y Windows):

- versión 3.3.4 de [R](https://cran.r-project.org/),
- versión 1.0.143 de [RStudio](https://www.rstudio.com/products/rstudio/download/), y
- versión 2.13.0 de [Git](https://git-scm.com/downloads).

También resulta imprescindible disponer de una cuenta en [GitHub](https://github.com/), cuyo registro solo precisa de un correo electrónico.

## Paquetes de R

Durante las sesiones de trabajo resultará necesario usar algunos paquetes de R. Lanzando la siguiente sentencia se instalarán los imprescindibles junto a sus dependencias:

```r
install.packages(pkgs = c("devtools", "DT", "ggplot2", "leaflet", "pander", "plotly",
                          "rmarkdown", "roxygen2", "shiny", "testthat"))
```

## Software opcional

Aunque se puede aprovechar el curso al 100 % con lo anteriormente expuesto, sería recomendable que quienes quieran experimentar con herramientas avanzadas acudan con una versión reciente y lo más completa posible de:

- el sistema de producción de documentos [TeX](https://es.wikipedia.org/wiki/TeX) (recomendamos la distribución de [Tex Live](https://tug.org/texlive/acquire-netinstall.html)),
- una [interfaz de usuario TeX](http://www.texstudio.org/),
- una [interfaz de usuario para Git](https://git-scm.com/downloads/guis) (aunque en gran medida se procurará trabajar desde terminal o RStudio), y
- un buen procesador de textos, siendo recomendable [Atom](https://atom.io/) o [Sublime Text](https://www.sublimetext.com/).
