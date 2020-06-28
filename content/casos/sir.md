---
title: "¿Cuál es el estado de la epidemia?"
name: "sir"
draft: false
descripcion: '<p>En teoría, el número de casos nuevos de COVID-19 por fecha
nos indica cuantos contagios ocurrieron en los días previos.
Sin embargo, en el mundo real
<a href="/clinicos#tiempo_deteccion">retraso típico de 11 días</a>. Además,
el muestreo no es perfecto y hay días que se identifican más o menos casos
por azar.</p>

<p> Esta gráfica muestra los resultados ajustar un
<a href="https://gabgoh.github.io/COVID/index.html"
target="_blank">modelo epidemiológico SEIR</a> a el número de casos
sintomáticos en días previos. El modelo capturar capturar cambios
en en el comportamientos social recalculandos la tasa de contactos cada 15 días.
Finalmente, el modelo incorpora el error de muestreo. Tomando en cuenta
estas fuentes de incertidumbre, el modelo puede pronosticar el número
de casos que eventualmente se identificarán para el día de hoy.</p>

<p>Ningún modelo captura la realidad completa, este modelo no puede pronosticar
un futuro lejano, ni estima el sub-registro de casos (para eso está el sistema
<a href="/casos#sir_centinela"> Centinela</a>). Por otro lado, este modelo
sí puede usarse para medir el
<a href="/casos#aplanamiento">aplanado de la curva</a>.</p>

<p>El código está
<a href="https://github.com/coronamex/visualizando/"
target="_blank">aquí</a>, y los estimados
<a href="https://raw.githubusercontent.com/coronamex/visualizando/master/estimados/bayes_seir_nacional.csv" target="_blank">aquí</a>.</p>
'
imagen: "imagenes/sir_nacional.png"
imagen2x: "imagenes/sir_nacional@2x.png"
alt: 'Resultados del modelos epidemiológico compartamentalizado SEIR.
El modelo se ajusta con datos de COVID-19 en Méxido a nivel nacional
hasta la fecha indicada. Además el modelo asume que la transmisibilidad
cambia cada 15 días. El modelo se ajusta con stan.'
Weight: 700
principal: false
secciones: ["casos"]
etiquetas: ["nacional", "casos", "síntomas", "estimado", "SIR", "modelo"]
---
