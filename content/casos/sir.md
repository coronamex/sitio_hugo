---
title: "¿Cuántos casos hay en México?"
name: "sir"
draft: false
descripcion: '<p>Esta gráfica muestra el número total de casos por la
fecha en que <span style="background-color: #7570b3">iniciaron sus
síntomas</span> y la fecha en que se
<span style="background-color: #1b9e77">confirmó</span> el caso.
Las líneas <span style="background-color: #d95f02">marrones</span>
muestran las estimaciones del número de casos totales basadas en un de un
<a href="https://gabgoh.github.io/COVID/index.html"
target="_blank">modelo epidemiológico</a>. Las diferentes líneas
muestran los resultados con diferentes parámetros. Este modelo se ajusta
a las fechas de inicio de sntomas, que son un indicador más preciso
que la fecha de confirmación del caso, y además nos permite estimar el cambio
en el número reproductivo (R0) del virus desde el inicio de las medidas de
mitigación.</p>
<p>La mayor fuente de incertidumbre es que el número de casos
positivos no corresponde con el total de casos. En México, esto
es esperado porque se usa un sistema de monitoreo Centinela que
es parecido a una encuesta. Puedes consultar las estimaciones basadas
en el sistema Centinela <a href="#sir_centinela">más abajo</a>.</p>
<p>El código para ajustar, simular y graficar el modelo está
<a href="https://github.com/coronamex/visualizando/blob/master/sir/sir.r"
target="_blank">aquí</a>.</p>'
imagen: "imagenes/sir_nacional.png"
imagen2x: "imagenes/sir_nacional@2x.png"
alt: 'Resultados del modelos epidemiológico compartamentalizado SEIR.
El modelo se ajusta con datos de COVID-19 en Méxido a nivel nacional
hasta la fecha indicada. Además el modelo asume que el número reproductivo
básico (R0) disminuye a partir de las medidas de mitigación. Los tiempos
de infección y de incubación son explorados en una matriz de valores,
mientras que R0 y el efecto de las
medidas de mitigación son optimizados por mínimos cuadrados. El ajuste
de datos utiliza las fechas de inicio de síntomas proporcionados por
el InDRE de la Dirección General de Epidemiología en la fecha más
reciente.'
Weight: 700
principal: false
secciones: ["principal", "casos"]
etiquetas: ["nacional", "casos", "síntomas", "estimado", "SIR"]
---
