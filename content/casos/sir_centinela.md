---
title: "¿Cuántos casos hay en México? (Centinela)"
name: "sir_centinela"
draft: false
descripcion: '<p>El sistema Centinela es similar a una encuesta y
permite estimar el número de casos reales del COVID-19 aún
sin diagnosticar a todos los contagiados. Los estimados oficiales
se publican con dos semanas de retraso, y el estimado oficial más
reciente es de
<a href="https://youtu.be/So48LCI6tSY?t=1349" target="_blank">
la semana epidemiológica 14 (3 de abril)</a>. Como la epidemia sigue
creciendo, el número de casos actual debe ser mayor.</p>

<p>La Secretaría de Salud (SSA) no publica todos los elementos
necesarios para reproducir sus estimados, así que hago algunas
simplificaciones y llego a un resultado similar. Esto nos permite
producir estimados en fechas más recientes.</p>

<p>Finalmente, podemos combinar los números del sistema Centinela
con un <a href="/casos#sir">modelo SEIR</a> para corregir por
el retraso en la detección de casos
y estimar el número de real casos el día de hoy. Como los números
de la SSA son más antiguos, el modelo SEIR no captura la desaceleración
más reciente de la epidemia. Todos los valores en esta
gráfica se calculan
<a href="https://github.com/coronamex/visualizando/blob/master/casos/centinela_preliminar.r" target="_blank">con este código</a>.</p>'
imagen: "imagenes/sir_nacional_centinela.png"
imagen2x: "imagenes/sir_nacional_centinela@2x.png"
alt: 'Casos nacionales acumulados estimados de COVID-19 en México
con datos del sistema de vigilancia epidemiológica centinela.
La gráfica muestra los estimados oficiales más recientes de la SSA que
se publican una vez por semana y con dos semanas de retraso.
La gráfica también muestra los estimados correspondientes de CoronaMex
que se actualizan diariamente con la base de datos abiertos de la
Secretaría de Salud.'
Weight: 800
principal: true
secciones: ["principal", "casos"]
etiquetas: ["nacional", "casos", "síntomas", "estimado", "centinela"]
---
