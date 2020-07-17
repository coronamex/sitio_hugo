---
title: "La epidemia se desacelera pero permanece"
name: "r_efectiva"
draft: false
descripcion: '<p>Las epidemias avanzan porque la enfermedad
se transmite de una persona a otra. La R efectiva (R_t) es el
número promedio de gente contagiada por cada persona que se enferma.
Si la R efectiva es más de uno los casos aumentan, mientras
que si la R efectiva es menos de uno los casos disminuyen.</p>

<p>Esta gráfica muestra la R efectiva en los estados del país.
confirmados. Prácticamente todos los estados han logrado dismunir la tasa
de contagios con respecto al inicio de la epidemia, aunque sólo unos pocos
la han logrado disminuir por debajo de 1, y en algunos hay aumentos
esporádicos. Además,
<a href="/municipios#top_zm_casos">varias</a>
<a href="/municipios#top_zm_casos2">zonas</a>
<a href="/municipios#top_zm_casos3">metropolitanas</a>
siguen mostrando una aceleración de su epidemia, por lo que la tasa
de contagios a nivel estatal puede ocultar diferencias locales.</p>

<p>A diferencia de los casos y los fallecimientos, la tasa de contagios
no se puede medir directamente sino que se estima indirectamente. Este análisis
adapta el método de <a href="https://rt.live/" target="_blank">rt.live</a>
que calcula este valor para EEUU. El código para estimar la R efectiva en
México está
<a href="https://github.com/coronamex/covid-model" target="_blank">aquí</a>
y los estimados más recientes
<a href="https://github.com/coronamex/covid-model/tree/mexico/R_efectiva/entidades" target="_blank"> aquí</a>.</p>'
imagen: "imagenes/r_efectiva.png"
imagen2x: "imagenes/r_efectiva@2x.png"
alt: 'R efectiva a través del tiempo en estados con al menos 500 casos.
Mediana e intervalo modal (Highest Density Posterior [HDP]) estimados
via MCMC.'
principal: true
Weight: 1140
secciones: ["estados", "principal"]
etiquetas: ["estados", "modelo", "estimados", "serie_tiempo"]
---
