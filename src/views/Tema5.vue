<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal
      .titulo-principal__numero
        span 5
      h1 Procedimientos técnicos en la recolección de información

    .row
      .col-lg-7
        .cajon-b.color-primario.cajon-b_2.p-3
          p(data-aos="fade-up") Un procedimiento de recogida de datos es, en principio, cualquier recurso utilizado por el investigador para acercarse a los fenómenos y extraer información de ellos. Dentro de cada instrumento concreto, se pueden distinguir dos aspectos diferentes: la forma y el contenido.
        .mt-3
          .cajon.color-secundario.p-5.mb-4
            p(data-aos="fade-up") #[strong La forma] del instrumento se refiere al tipo de aproximación que establecemos con lo empírico, a las técnicas que utilizamos para esta tarea; una exposición más detallada de las principales se ofrece al lector en este mismo capítulo.
            p.mt-3(data-aos="fade-up") #[strong El contenido] se expresa en la especificación de los datos que necesitamos obtener; se concreta, por tanto, en una serie de ítems que no son más que los mismos ítems sin dictar que nos permiten medir las variables, pero que ahora toman la forma de preguntas, puntos a observar, elementos a registrar, etc. 
      .col-lg-5
        img(src="@/assets/curso/tema5/1.svg" data-aos="fade-left")

    p.mt-5(data-aos="fade-up") Es a través de una adecuada construcción de los instrumentos de recogida como la investigación consigue entonces la necesaria correspondencia entre teoría y hechos. Es más, podríamos decir que es gracias a ellos que ambos términos quedan efectivamente vinculados. Si los instrumentos son defectuosos en un proyecto de investigación, inevitablemente surgirán algunas de las siguientes dificultades: o bien los datos recogidos no satisfacen las preguntas iniciales, o bien los datos obtenidos están distorsionados y desvirtuados porque el instrumento elegido no se adapta al tipo de hechos estudiados. En ambos casos, seguramente se habrán producido uno o varios errores en las fases anteriores del proceso de investigación.

    p.mt-3(data-aos="fade-up") Será entonces necesario volver atrás (lo que es mucho más frecuente de lo que el lector puede imaginar) y revisar las diferentes tareas realizadas, hasta llegar a una mejor resolución del problema. Así, situados en su perspectiva, se pasa a estudiar las principales técnicas de recogida de datos que se suelen utilizar, no sin antes hacer algunas aclaraciones sobre los tipos de datos que se presentan al investigador.

    .row.mt-5
      .col-md-6.p-5.text-center(style="margin:0px;background-color:#2CC3B2;border-top-left-radius:15px;border-bottom-left-radius:15px;")
        img(src="@/assets/curso/tema5/2.svg" data-aos="fade-up" style="display:inline;max-width:100px;")
        p.mt-4.text-white(data-aos="fade-up") Los datos primarios y secundarios no son dos tipos de información esencialmente diferentes, sino partes de una misma secuencia: #[br] todos los datos secundarios han sido primarios en sus orígenes y todos los datos primarios, desde el momento en que el investigador concluye su trabajo, se convierten en datos secundarios para otros.  En la experiencia cotidiana, también recurrimos constantemente a ambos tipos de fuentes.
      .col-md-6.p-5.text-center(style="margin:0px;background-color:#7B1FA2;border-top-right-radius:15px;border-bottom-right-radius:15px;")
        img(src="@/assets/curso/tema5/3.svg" data-aos="fade-up" style="display:inline;max-width:100px;")
        p.mt-4.text-white(data-aos="fade-up") Imagine que ha llegado por primera vez a una ciudad y quiere ir a determinados lugares. Para lograr su objetivo puede tomar nota de las calles que va transitando, la ubicación de los monumentos, las plazas y las principales tiendas, y de esta manera formarse una idea que le sirva de referencia para ubicarse. También puede preguntar a los habitantes sobre sus puntos de interés, dirigiéndose a los que considere pueden estar mejor informados. Al utilizar ambos recursos estaría recogiendo datos primarios, en el primer caso, mediante la técnica de observación y en el segundo con la ayuda de entrevistas. Además, puede recurrir a la información proporcionada por planos, mapas o guías turísticas. En este último caso, las fuentes de sus datos serán materiales previamente recopilados y organizados por otras personas, por lo que serán datos secundarios.

    p.mt-5(data-aos="fade-up") Para conocer un poco más sobre las diferentes técnicas de recolección de información, tendrá la posibilidad de visualizar el siguiente recurso en el cual se abordan algunos referentes importantes y su forma de utilización.

    .tarjeta.color-primario.p-3.mt-5(style="background: linear-gradient(#5c22c3, #5c8dfd)")
      .row.justify-content-around.align-items-center
        .col-3.col-sm-2.col-lg-1
          img(src="@/assets/curso/tema5/4.svg")
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              h3.mb-1.text-white Recolección de datos
              p.text-small.text-white Conoce sobre las diferentes técnicas de recolección de datos y su importancia en la logística de comercialización de productos.
            .col-sm-auto
              a.boton.texto-blanco(href="https://www.youtube.com/embed/TinhDQv6UH8" target="_blank")
                span Descargar
                i.fas.fa-file-download  





</template>

<script>
export default {
  name: 'Tema5',
  data: () => ({}),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>
<style lang="sass">
.cajon-b.color-primario:before
  background-color: #CFDDFC
.cajon-b:before
  bottom: 76%
.cajon-b_2:before
  bottom: 20%
.color2:before
  background-color: #34D9C7 !important
.color2
  background: url("../assets/curso/tema2/3.svg")
  background-repeat: no-repeat
.bloque-texto-a:before
  left: 45%
.pasos-a.color-acento-botones .pasos-a__circle div
    color: white
.pasos-a.color-acento-botones .pasos-a__circle
    background-color: #5C22C3
.pasos-a.color-acento-botones .pasos-a__linea .hor-line
    border-top-color: #BA68C8
.pasos-a.color-acento-botones .pasos-a__linea__esquina__linea
    border-color: #BA68C8
.pasos-a.color-acento-botones .pasos-a__numero::after
    border-left-color: #BA68C8
.tabs-a.color-acento-botones .tabs-a__tab__selected
    background-color: #34D9C7
.tabs-a.color-acento-botones .tabs-a__tab__selected:before
    background-color: #34D9C7
.tarjeta.color-acento-botones--borde
    background-color: #F6FEFD
    border: none !important
.tabs-a.color-acento-botones .tabs-a__tab:hover, .tabs-a.color-acento-botones .tabs-a__tab:active, .tabs-a.color-acento-botones .tabs-a__tab:focus
    background-color: #34D9C7
.cont_caja_1
  background: url("../assets/curso/tema2/10.svg")
  background-repeat: no-repeat
  background-position: center
.linea-tiempo-d__item--selected .linea-tiempo-d__item__content
    background-color: #F2FEFD !important
.linea-tiempo-d__item--selected .linea-tiempo-d__item__number
  background-color: #F2FEFD !important
.linea-tiempo-d__item--selected .linea-tiempo-d__item__number span
  font-weight: bold
  color: #12263F
.cajon.color-secundario
    background-color: #DBF5F2
.cajon.color-secundario:before
    background-color: #34D9C7
</style>
