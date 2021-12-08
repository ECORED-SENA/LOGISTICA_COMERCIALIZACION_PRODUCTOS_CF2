<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal
      .titulo-principal__numero
        span 1
      h1 Clasificación de proveedores e información de mercancías

    .row
      .col-md-7
        .cajon-b.color-primario.p-3
          p(data-aos="fade-up") La selección de proveedores es un proceso que está presente en toda organización, ya que la compra de bienes y servicios como maquinaria, materias primas, servicios de limpieza, entre otros, es elemental, por lo que este proceso debe estar enfocado a una investigación de calidad.
          p.mt-3(data-aos="fade-up") Es conocido, en la mayoría de las empresas, que al departamento de compras o abastecimiento se delega realizar la investigación y selección de los proveedores que mejor se adapten a las necesidades de la organización. La clave en la selección de proveedores de un producto o servicio radica en el valor de saber qué criterios utilizar para seleccionarlos, ya que se debe tener en cuenta qué tipo de efecto tendrán los productos o servicios que proporcionan y si esto tendrá un efecto positivo en la productividad, la calidad y la competitividad de la propia organización.
          p.mt-3(data-aos="fade-up") La búsqueda y selección de proveedores se puede hacer por diferentes motivos, ya sea porque la organización comienza a operar y no tiene proveedores, la organización ya tiene proveedores, pero no satisfacen sus necesidades y necesita mejor calidad, o quiere ampliar la cartera de proveedores para que la organización tenga un parámetro de comparación y ver si quiere mejorar.
      .col-md-5
        img(src="@/assets/curso/tema1/1.svg" data-aos="fade-left")

    .bloque-texto-a.color-primario.color2.p-4.p-md-5.mt-5.col-md-9.m-auto 
      .row.m-0.align-items-center.justify-content-between
        .col-lg-4.mb-4.mb-lg-0
        .col-lg-8
          .bloque-texto-a__texto.p-4
            p(data-aos="fade-up") Identificar los proveedores es la primera fase para su selección y su objetivo es implementar un listado de las organizaciones que fabrican los diferentes productos, según las necesidades de las empresas, para solicitarles información sobre estas.

    p.mt-5(data-aos="fade-up") Una vez se tiene la información de los proveedores, se hace la selección de los más adecuados, considerando los criterios seleccionados para minimizar la proporción de proveedores. Un punto aconsejable, es no tener a un solo distribuidor, ya que si este fracasa, la organización no se queda desabastecida.
    p.mt-3(data-aos="fade-up") De acuerdo con la fase o la etapa en la que se encuentra la empresa, se identifican los proveedores acordes a lo siguiente:

    .row.mt-5
      .col-md-4.p-4.text-center(style="margin:0px;background-color:#D8ECFF;border-top-left-radius:50px;")
        img(src="@/assets/curso/tema1/3.svg" data-aos="fade-up" style="display:inline;max-width:100px;")
        h4.mt-4(data-aos="fade-up") Empresa que inicia actividad
        p.mt-4(data-aos="fade-up") Busca toda clase de proveedores
      .col-md-4.p-4.text-center(style="margin:0px;background-color:#F3F9FF")
        img(src="@/assets/curso/tema1/4.svg" data-aos="fade-up" style="display:inline;max-width:100px;")
        h4.mt-4(data-aos="fade-up") Empresa que cuenta con proveedores
        p.mt-4(data-aos="fade-up") No está satisfecho con proveedores
      .col-md-4.p-4.text-center(style="margin:0px;background-color:#D8ECFF;border-top-right-radius:50px;")
        img(src="@/assets/curso/tema1/5.svg" data-aos="fade-up" style="display:inline;max-width:100px;")
        h4.mt-4(data-aos="fade-up") Empresa que requiere ampliar la cartera de proveedores
        p.mt-4(data-aos="fade-up") Mejoras de gestión comercial

    p.mt-5(data-aos="fade-up") Para la selección de un adecuado proveedor, se debe averiguar las diferentes opciones que se tendrán y que estos cumplan con cada uno de los requerimientos que la empresa tiene, para ello, se debe borrar uno a uno acorde a la lista de criterios y distintas consideraciones, hasta minimizar a unos pocos, a los cuales se les solicitará una cotización. De acuerdo a lo anterior, los criterios que se deben tener en cuenta para la selección de proveedores son:

    .col-md-10.m-auto
      .row.mt-5
        .col-lg-4
          .tarjeta.tarjeta-flip.color-primario(@mouseover="indicadorTarjetaFlip = false")
            .indicador--hover(v-if="indicadorTarjetaFlip")
            .tarjeta-flip__contenedor
              .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema1/6.svg')})`}")
              .tarjeta-flip__contenido.p-5(style="background-color:#34D9C7;")
                h3.mt-5.mb-5.text-white.text-center Tiempo de entrega
        .col-lg-4
          .tarjeta.tarjeta-flip.color-primario(@mouseover="indicadorTarjetaFlip = false")
            .indicador--hover(v-if="indicadorTarjetaFlip")
            .tarjeta-flip__contenedor
              .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema1/7.svg')})`}")
              .tarjeta-flip__contenido.p-5(style="background-color:#7B1FA2;")
                h3.mt-5.mb-5.text-white.text-center Formas y plazos de pago
        .col-lg-4
          .tarjeta.tarjeta-flip.color-primario(@mouseover="indicadorTarjetaFlip = false")
            .indicador--hover(v-if="indicadorTarjetaFlip")
            .tarjeta-flip__contenedor
              .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema1/8.svg')})`}")
              .tarjeta-flip__contenido.p-5(style="background-color:#34D9C7;")
                h3.mt-5.mb-5.text-white.text-center Condiciones de transporte

    .col-md-10.m-auto
      .row.mt-5
        .col-lg-4
          .tarjeta.tarjeta-flip.color-primario(@mouseover="indicadorTarjetaFlip = false")
            .indicador--hover(v-if="indicadorTarjetaFlip")
            .tarjeta-flip__contenedor
              .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema1/9.svg')})`}")
              .tarjeta-flip__contenido.p-5(style="background-color:#7B1FA2;")
                h3.mt-5.mb-5.text-white.text-center Descuentos por volumen
        .col-lg-4
          .tarjeta.tarjeta-flip.color-primario(@mouseover="indicadorTarjetaFlip = false")
            .indicador--hover(v-if="indicadorTarjetaFlip")
            .tarjeta-flip__contenedor
              .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema1/10.svg')})`}")
              .tarjeta-flip__contenido.p-5(style="background-color:#34D9C7;")
                h3.mt-5.mb-5.text-white.text-center Calidad
        .col-lg-4
          .tarjeta.tarjeta-flip.color-primario(@mouseover="indicadorTarjetaFlip = false")
            .indicador--hover(v-if="indicadorTarjetaFlip")
            .tarjeta-flip__contenedor
              .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema1/11.svg')})`}")
              .tarjeta-flip__contenido.p-5(style="background-color:#7B1FA2;")
                h3.mt-5.mb-5.text-white.text-center Envases y embalajes

    p.mt-5(data-aos="fade-up") Una vez definidos y ordenados jerárquicamente los criterios de selección, el siguiente paso es seleccionar a los proveedores aplicando un determinado método, el cual debe ser coherente con el análisis del contexto, las realidades de la cadena de suministro y los criterios seleccionados por cada una de las organizaciones, según De Boer Weger y Telgen indican que el método elegido puede aumentar la eficiencia de la decisión de compra a partir de:

    .row.mt-5
      .col-md-7
        PasosA.color-acento-botones(tipo="l")
          div
            p(data-aos="fade-up") Permitir un procesamiento más rápido y automatizado de los datos, así como el análisis de toda la información relevante para tomar una decisión.
          div
            p(data-aos="fade-up") Permitir un almacenamiento más eficiente de todos los procesos de decisión para proporcionar el acceso a la información en casos futuros.
          div
            p(data-aos="fade-up") Eliminar criterios y alternativas redundantes en los procesos de decisión.
          div
            p(data-aos="fade-up") Facilitar una comunicación más eficiente y justificar los resultados de los procesos de decisión.

      .col-md-5
        img(src="@/assets/curso/tema1/12.svg" data-aos="fade-left")

    p.mt-5(data-aos="fade-up") Una tendencia detectada en la mayoría de los autores consultados es que primero aplican un método de precalificación o aproximación que luego se complementa con un método de selección y optimización final, para apoyar una decisión más adecuada, por lo que proponen la solución del problema de selección de proveedores a partir de la integración de métodos complementarios. De acuerdo con esto, es necesario dividir los métodos de selección en dos grupos: métodos de precalificación y métodos de selección final.

    TabsA.color-acento-botones.mt-5
      .tarjeta.color-acento-botones--borde.p-4(titulo="Métodos de precalificación")
        .row
          .col-md-6
            h4 Métodos de precalificación
            p.mt-2 De Boer, define la precalificación como el proceso de reducción de la base de proveedores a un conjunto más reducido de proveedores potenciales. También se conocen como métodos de asistencia, ya que permiten obtener una solución inicial o estructurar procesos de decisión basados en datos cualitativos que, a partir de ciertos procedimientos, se convierten en los mismos para aplicar métodos de optimización.
          .col-md-6
            img(src="@/assets/curso/tema1/13.svg")
      .tarjeta.color-acento-botones--borde.p-4(titulo="Métodos categóricos")
        .row
          .col-md-6
            h4 Métodos categóricos
            p.mt-2 Permiten la evaluación y selección de proveedores a partir del análisis cualitativo de la información histórica y de la experiencia previa que la empresa u otros compradores han tenido con un determinado proveedor, la evaluación consiste en categorizar el desempeño de los proveedores en criterios calificados como positivos, neutros o negativos. Tras asignar una calificación a cada uno de los criterios, el comprador procede a tomar una decisión final.
          .col-md-6
            img(src="@/assets/curso/tema1/14.svg")
      .tarjeta.color-acento-botones--borde.p-4(titulo="Técnicas difusas")
        .row
          .col-md-6
            h4 Técnicas difusas
            p.mt-2 Es una de las mejores herramientas para tratar datos, información inexacta o imprecisa, obtenida de situaciones complejas que no pueden describirse razonablemente en expresiones cuantitativas convencionales. Generalmente, estas variables se expresan como "muy poco", "poco", "medio", "alto", etc. Este método se utiliza ampliamente para evaluar a los proveedores en el sector de la ingeniería y el desarrollo tecnológico.
          .col-md-6
            img(src="@/assets/curso/tema1/15.svg")
      .tarjeta.color-acento-botones--borde.p-4(titulo="Razonamiento basado en casos")
        .row
          .col-md-6
            h4 Razonamiento basado en casos
            p.mt-2 Es un sistema de #[em software] gestionado por una base de datos que recoge información relevante de los procesos de decisión y evaluación de situaciones o casos ocurridos con anterioridad. Esto permite al responsable de la toma de decisiones, basarse en información útil y en la experiencia de situaciones conocidas. El modelo posibilita una gestión exitosa de la contratación, ya que al tener en cuenta los avances logrados en procesos anteriores, no da lugar a que se vuelvan a cometer los mismos errores, sobre todo porque reutiliza la información relevante para proponer un modelo combinado.
          .col-md-6
            img(src="@/assets/curso/tema1/16.svg")
      .tarjeta.color-acento-botones--borde.p-4(titulo="Métodos de selección final")
        .row
          .col-md-6
            h4 Métodos de selección final
            p.mt-2 Una vez obtenida una primera aproximación a la decisión final, es necesario llevar a cabo un proceso que permita alcanzar la decisión final a partir de la utilización de algún procedimiento o el uso de algunas técnicas exactas. En este caso, es necesario aplicar modelos que se alejen de los juicios y resultados subjetivos y se centren en la formulación explícita de una función con objetivo optimizable, más aplicada en la selección de proveedores.
          .col-md-6
            img(src="@/assets/curso/tema1/17.svg")


</template>

<script>
export default {
  name: 'Tema1',
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
.color2:before
  background-color: #34D9C7 !important
.color2
  background: url("../assets/curso/tema1/2.svg")
  background-repeat: no-repeat
.bloque-texto-a:before
  left: 45%
.pasos-a.color-acento-botones .pasos-a__circle div
    color: white
    text-transform: lowercase
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
.tarjeta-flip__contenido h3
  word-break: break-word
.tarjeta-flip__contenido
  display: flex
  align-items: center
  place-content: space-around
</style>
