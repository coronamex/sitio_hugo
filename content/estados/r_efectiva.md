---
title: "La epidemia se desacelera pero permanece"
name: "r_efectiva"
draft: false
descripcion: '<p>Las epidemias avanzan porque la enfermedad
se transmite de una persona a otra. La <i>R efectiva</i> (R_t) es el
número promedio de contagios por cada persona que se enferma.
Si la <i>R efectiva</i> es más de uno los casos aumentan, mientras
que si la <i>R efectiva</i> es menos de uno los casos disminuyen.</p>

<p>Esta gráfica muestra la evolución de la <i>R efectiva</i> en los estados
del país, y en la mayor zona metropolitana de cada entidad. En general,
este indicador a disminuido en todos los estados desde el inicio de
la epidemia, pero pocas entidades logran un valor consistentemente por debajo
de uno, y los casos siguen
<a href="/estados#estados_casos1">aumentando</a>
<a href="/estados#estados_casos2">en</a>
<a href="/estados#estados_casos3">muchos</a>
<a href="/estados#estados_casos4">estados</a>.</p>

<p><a href="/municipios#vm_casos">Las</a>
<a href="/municipios#top_zm_casos">zonas</a>
<a href="/municipios#top_zm_casos2">metropolitanas</a>
<a href="/municipios#top_zm_casos3">han</a>
sido las
<a href="/muertes#muertes_tipomun">más afectadas</a>
por lo que la <i>R efectiva</i> de un estado suele corresponder
a la de su mayor zona metropolitana, pero hay algunas diferencias.
Estas diferencias pueden ser causadas por zonas metropolitanas que cruzan
fronteras estatales, la presencia de múltiples centros urbanos en una
entidad, y la <a href="/municipios#n_municipios">expansión geográfica</a>
de la epidemia a nuevos municipios.</p>

<p>A diferencia de los casos y los fallecimientos, la tasa de contagios
no se puede medir directamente sino que se estima indirectamente. Este análisis
adapta el método de <a href="https://rt.live/" target="_blank">rt.live</a>
que calcula este valor para EEUU. El código para estimar la R efectiva en
México está
<a href="https://github.com/coronamex/covid-model" target="_blank">aquí</a>
y los estimados más recientes
<a href="https://github.com/coronamex/covid-model/tree/mexico/R_efectiva" target="_blank"> aquí</a>.</p>'
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
