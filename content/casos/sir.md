---
title: "¿Cuál es el estado de la epidemia?"
name: "sir"
draft: false
descripcion: '<p>El número de casos sintomáticos de COVID-19 en una fecha
refleja el número de contagios en días previos. Sin embargo, hay un
<a href="/clinicos#tiempo_deteccion">retraso típico de 11 días</a>
en la confirmación de un caso.</p>

<p>Afortunadamente podemos adaptar un
<a href="https://gabgoh.github.io/COVID/index.html" target="_blank">modelo epidemiológico SEIR</a>
y estimar el estado más probable de la epidemia al día de hoy. La estimación
se realiza con
<a href="https://github.com/coronamex/visualizando/blob/master/casos/stan_seir.r" target="_blank">este código</a>
y los valores numéricos están
<a href="https://github.com/coronamex/visualizando/tree/master/estimados" target="_blank">aquí</a>.
Hubo un aparente descenso en el número de casos en diciembre, aunque esto
podría deberse a una menor capacidad
de registro de casos durante los días festivos, sobretodo porque
<a href="/muertes#muertes_tipomun">los fallecimientos sigueron aumentando</a>.
En lo que va del 2021, la epidemia no ha dejado de crecer.
Sólo se muestran los seis meses más recientes.</p>

<p>Ningún modelo captura la realidad completa, este modelo no puede pronosticar
un futuro lejano, ni estima el sub-registro de casos (para eso está el sistema
<a href="/casos#sir_centinela"> Centinela</a>). Este modelo tampoco considera
variaciones locales
<a href="/estados#r_efectiva">entre</a>
<a href="/estados#estados_casos_100mil">estados</a>
y <a href="/municipios#vm_casos">zonas</a>
<a href="/municipios#top_zm_casos.md">metropolitanas</a>.
Por otro lado, este modelo sí puede usarse para medir el
<a href="/casos#aplanamiento">aplanado de la curva</a>.</p>
'
imagen: "imagenes/sir_nacional.png"
imagen2x: "imagenes/sir_nacional@2x.png"
alt: 'Resultados del modelos epidemiológico compartamentalizado SEIR.
El modelo se ajusta con datos de COVID-19 en Méxido a nivel nacional
hasta la fecha indicada. Además el modelo asume que la transmisibilidad
cambia cada 15 días. El modelo se ajusta con stan.'
Weight: 600
principal: true
secciones: ["principal", "casos"]
etiquetas: ["nacional", "casos", "síntomas", "estimado", "SIR", "modelo"]
---
