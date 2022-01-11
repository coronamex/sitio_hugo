---
title: "¿Cuál es el estado de la epidemia?"
name: "sir"
draft: false
descripcion: '<p>Desde la última semana del 2021 vemos un incremento acelerado
en el número de casos reportados. Una combinación de la movilidad por las
fiestas y la capacidad de Ómicron de infectar incluso a personas vacunadas.
Afortunadamente la vacunación
<a href="/clinicos#mortalidad_edad_tipomun">sigue protegiendo</a>
contra las consecuencias más graves de la enfermedad y no hemos visto un
incremento en los <a href="/muertes#muertes_tipomun">fallecimientos</a>.
Esto no quiere decir que no haya peligro y debemos vacunarnos si no lo
hemos hecho. Este patrón se ha reproducido en la mayoría de los
<a href="/estados#estados_casos1">entre estados</a>
y <a href="/municipios#top_zm_casos">zonas metropolitanas</a> del país.
</p>

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
