---
title: "¿Cuál es el estado de la epidemia?"
name: "sir"
draft: false
descripcion: '<p>Tras meses de descenso sostenido tanto en contagios como en
<a href="/muertes#muertes_tipomun">fallecimientos</a>, vemos un aumento pequeño
pero claro en el número de casos a nivel nacional. Hay diferencias entre
<a href="/estados#estados_casos1">entidades</a>
pero la tendencia global es clara. No sabemos si se trata del principio de una
tercera "ola", y hasta cierto punto, es inevitable los contagios aumenten
cuando mejora el
<a href="https://coronavirus.gob.mx/semaforo/" target="_blank">semáforo</a>.
Aún si se trata de una nueva "ola", la vacunación
<a href="/clinicos#mortalidad_edad_tipomun">está</a>
<a href="/clinicos#casos_def_por_edad">funcionando</a>,
por lo que es importante vacunarse tan pronto sea nuestro turno.</p>

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
