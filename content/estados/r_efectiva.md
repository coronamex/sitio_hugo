---
title: "No se ha detenido la epidemia"
name: "r_efectiva"
draft: false
descripcion: '<p>Las epidemias avanzan porque la enfermedad
se transmite de una persona a otra. La R efectiva (R_t) es el
número promedio de gente contagiada por cada persona que se enferma.
Si la R efectiva es más de uno los casos aumentan, mientras
que si la R efectiva es menos de uno cada vez hay menos casos.</p>

<p>Lograr una tasa de contagios por contagiado de menos de uno es la única
manera en que la cantidad de casos disminuya. En otras palabras, un
R efectiva menor a uno indica que se pasó el pico epidémico. De acuerdo a esta
métrica, varios estados han mostrado una disminución en el número de contagios
por caso, pero en ningún caso la R efeciva es menor a uno, indicando que no se ha
pasado el pico epidémico.</p>

<p>Esta gráfica muestra la R efectiva en estados con al menos 500 casos
confirmados. La línea más gruesa muestra el mejor estimado (mediana) y el
área sombreada representa el rango más probable de valores (intervalo
modal de 90%). Los estimados se actualizan cada noche con los datos
más recientes. Debido al <a href="/clinicos#">retraso</a> en la detección
de casos aunque sólo podemos estimar la R efectiva hasta hace 5 días.</p>

<p>Este análisis se basa en
<a href="https://rt.live/" target="_blank">rt.live</a>
que calcula R_t para EEUU. El código para estimar la R efectiva en
México está
<a href="https://github.com/coronamex/visualizando/blob/master/estados/rt.live.ipynb" target="_blank">aquí</a>
y los estimados
<a href="https://raw.githubusercontent.com/coronamex/visualizando/master/estimados/rt_live_estimados.csv" target="_blank"> aquí</a>.</p>'
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
