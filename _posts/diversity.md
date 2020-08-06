---
layout: post
title: El valor de la diversidad
subtitle : Intersección y ventajas culturales de la extensión de las redes personales
tags: [Social Networks, Social capital, Heterogeneity]
author: Roberto Cantillan
comments : False
---

**El valor de la diversidad (extensity)**

La heterogeneidad describe patrones estructurales de interacción social que 
pueden mantener o socavar la integración y la desigualdad social (Blau, 1974, 
1977; Perry et al., 2018). A nivel de ego, la heterogeneidad de contactos 
accesibles facilita la movilidad de las personas y la intersección de grupos y 
ocupaciones sociales en la estructura. El valor de los lazos intergrupales está 
fundamentado en su baja probabilidad. De esta manera, mantener lazos débiles 
hacia otros círculos sociales, si bien es extremadamente difícil (Lin, 2002), 
otorga acceso a recursos no redundantes, lo cual mejora el rendimiento de las 
inversiones y las oportunidades de los individuos. 

Por lo general, su estudio se ha realizado como una perspectiva egocentrada 
dentro del campo de los análisis de capital social (Abascal & Baldassarri, 2015; 
Côté & Erickson, 2009; Erickson, 2004; Glanville, 2016; Lin, 2002; Rapp & 
Freitag, 2015; Son & Lin, 2008). La diversidad deriva del concepto “Extensity”, 
propuesto por Nan Lin (2002), para captar la heterogeneidad de posiciones y 
recursos al alcance en las redes personales lejanas (Lin, 2001: p. 63). En esta 
línea, Erickson (2003, 2004), indica que las personas no solo son más saludables 
y felices cuando tienen íntimos con los cuales se establecen relaciones 
recíprocas de cuidado. Sino que, también, les va mejor cuando conocen 
casualmente a muchas personas diferentes (2003: p. 2). El argumento básico es 
que conocer a variados tipos de personas incrustadas en diferentes contextos 
sociales, mejora las probabilidades de acceder a recursos diversos, lo cual se
asocia a su vez con mejores probabilidades de conseguir un buen trabajo, 
desarrollar una gran variedad de intereses culturales, sentirse en control 
sobre la vida y estar saludable (Erickson, 2003; Son & Lin, 2008). De esta 
manera, analizar las ocupaciones es importante por que las personas con 
diferentes trabajos probablemente difieran mucho entre ellas y, por que la 
posición en el mercado de trabajo refleja nuestra herencia y accesos que dan 
forma a nuestra manera de vivir (como los gustos y estilos de vida en general) 
(Erickson, 2003, 2004). 

Por lo general, esta tarea analítica se ha abordado a través del uso de una 
técnica conocida como “generador de posiciones”  (Lin & Dumin, 1986) la cual 
puede usarse en toda sociedad en la que se hayan catalogado las ocupaciones, 
los prestigios ocupacionales y/o los índices socioeconómicos relacionados con 
el trabajo. En efecto, en los últimos años se ha transformado en una potente 
herramienta para el análisis comparativo de los rendimientos de capital social 
entre las poblaciones (Gaag et al., 2008). Vale la pena enunciar, siguiendo a 
Lin (2002), que las medidas asociadas al generador de posiciones (ej. Variedad 
de composición de la red) pueden tener un sesgo hacia la descripción de los 
procesos que circunscriben acciones individuales de tipo instrumental. La 
estrategia estándar del generador es presentar al encuestado una lista de 
ocupaciones que van desde muy alto a muy bajo en prestigio, y preguntar si el 
encuestado conoce a alguien que desarrolle cada una de las ocupaciones (por lo 
general se aleatoriza el orden). Cuanto mayor sea el número de ocupaciones 
dentro de las cuales un encuestado tiene un contacto, mayor será la diversidad 
en la red social del encuestado. 







```{r setup, include = FALSE}
knitr::opts_chunk$set(
  collapse = TRUE,
  comment = "#>"
)
```

Vignettes are long form documentation commonly included in packages. Because they are part of the distribution of the package, they need to be as compact as possible. The `html_vignette` output type provides a custom style sheet (and tweaks some options) to ensure that the resulting html is as small as possible. The `html_vignette` format:

- Never uses retina figures
- Has a smaller default figure size
- Uses a custom CSS stylesheet instead of the default Twitter Bootstrap style

## Vignette Info

Note the various macros within the `vignette` section of the metadata block above. These are required in order to instruct R how to build the vignette. Note that you should change the `title` field and the `\VignetteIndexEntry` to match the title of your vignette.

## Styles

The `html_vignette` template includes a basic CSS theme. To override this theme you can specify your own CSS in the document metadata as follows:

    output: 
      rmarkdown::html_vignette:
        css: mystyles.css

## Figures

The figure sizes have been customised so that you can easily put two images side-by-side. 

```{r, fig.show='hold'}
plot(1:10)
plot(10:1)
```

You can enable figure captions by `fig_caption: yes` in YAML:

    output:
      rmarkdown::html_vignette:
        fig_caption: yes

Then you can use the chunk option `fig.cap = "Your figure caption."` in **knitr**.

## More Examples

You can write math expressions, e.g. $Y = X\beta + \epsilon$, footnotes^[A footnote here.], and tables, e.g. using `knitr::kable()`.

```{r, echo=FALSE, results='asis'}
knitr::kable(head(mtcars, 10))
```

Also a quote using `>`:

> "He who gives up [code] safety for [code] speed deserves neither."
([via](https://twitter.com/hadleywickham/status/504368538874703872))
