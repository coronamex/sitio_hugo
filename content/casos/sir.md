---
title: "¿Cuántos casos hay en México?"
name: "sir"
draft: false
descripcion: '<p>Como se ve en esta gráfica, hay un retraso entre
cuando una persona enferma de COVID-19
<span style="background-color: #cab2d6">muestra síntomas</span> y la
fecha en que el caso se
<span style="background-color: #b2df8a">confirma</span>. Por lo tanto,
el día de hoy debe haber más casos que los confirmados. Las líneas
<span style="background-color: #dfc27d">marrones</span>
muestran estimados de un
<a href="https://gabgoh.github.io/COVID/index.html"
target="_blank">modelo epidemiológico SEIR</a> con diferentes parámetros.</p>
<p>El código para ajustar, simular y graficar el modelo está
<a href="https://github.com/coronamex/visualizando/blob/master/casos/sir.r"
target="_blank">aquí</a>. El algoritmo busca los parámetros que mejor
reproducen los casos que mostraron síntomas hasta hace dos semanas, y luego
proyecta como la epidemia habría continuado desde entonces. Como las medidas
de mitigación pueden desacelerar la epidemia, el algoritmo
también re-calcula el
<a href="https://es.wikipedia.org/wiki/Ritmo_reproductivo_b%C3%A1sico" target="_blank">
ritmo reproductivo básico</a> cada diez días (líneas rojas). Todos los
valores numéricos se pueden
<a href="https://github.com/coronamex/visualizando/blob/master/seir_estimados.csv" target="_blank">descargar</a>.</p>

<p>Este ejercicio no puede decirnos que pasa con la proporción de
casos no detectados, para eso México usa un sistema de
<a href="/casos#sir_centinela"> vigilancia Centinela</a>.</p>
<p>Esta gráfica se actualiza unas horas después que el resto del sitio.</p>'
imagen: "imagenes/sir_nacional.png"
imagen2x: "imagenes/sir_nacional@2x.png"
alt: 'Resultados del modelos epidemiológico compartamentalizado SEIR.
El modelo se ajusta con datos de COVID-19 en Méxido a nivel nacional
hasta la fecha indicada. Además el modelo asume que el número reproductivo
básico (R0) cambia cada cierto número de días (10) indicados
por las líneas rojas. Los tiempos
de infección y de incubación son explorados en una matriz de valores,
mientras que R0 y su cambio en el tiempo son optimizados por mínimos
cuadrados usando "Simulated Annealing". El ajuste
de datos utiliza las fechas de inicio de síntomas proporcionados por
los datos abiertos de la SSA en la fecha más reciente.'
Weight: 700
principal: false
secciones: ["casos"]
etiquetas: ["nacional", "casos", "síntomas", "estimado", "SIR", "modelo"]
---
