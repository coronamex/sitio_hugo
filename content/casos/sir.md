---
title: "¿Cuál es el estado de la epidemia?"
name: "sir"
draft: false
descripcion: '<p>En estos momentos la actividad epidémica es relativamente
baja, y todos los indicadores se encuentra claramente cerca de sus mínimos
históricos. Esto no significa que el COVID-19 haya sido o vaya a ser erradicado,
y lo más probable es que en el algún momento del futuro los contagios vuelva
a aumentar. Nuestra mejor defensa siguen siendo las vacunas.</p>

<p>La gráfica muestra el número de casos registrados (barras) y utiliza
<a href="https://gabgoh.github.io/COVID/index.html" target="_blank">modelo epidemiológico SEIR</a>
para estimar el estado más probable de la epidemia al día de hoy (áreas
sombreadas). La estimación se realiza con
<a href="https://github.com/coronamex/visualizando/blob/master/casos/stan_seir.r" target="_blank">este código</a>
y los valores numéricos están
<a href="https://github.com/coronamex/visualizando/tree/master/estimados" target="_blank">aquí</a>.
Sólo se usan los últimos 6 meses.</p>

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
