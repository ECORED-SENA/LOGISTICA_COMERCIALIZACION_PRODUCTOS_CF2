<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal
      .titulo-principal__numero
        span 6
      h1 Reporte y registro de novedades

    .row
      .col-md-7
        .cajon-b.color-primario.p-3
          p(data-aos="fade-up") En la cadena de suministro, la trazabilidad puede ser una cuestión tanto reglamentaria como ética o medioambiental. La trazabilidad se está convirtiendo cada vez más en un criterio fundamental para los esfuerzos de sostenibilidad, relacionados con las cadenas de suministro, en las que conocer al productor, a los trabajadores y a otros eslabones, se erige como un factor necesario que subyace a las afirmaciones acertadas sobre el impacto social, económico o medioambiental. Los minoristas respetuosos con el medio ambiente pueden optar por poner a disposición de los clientes la información relativa a su cadena de suministro, ilustrando el hecho de que los productos que venden se elaboran en fábricas con condiciones laborales seguras, por trabajadores que ganan un salario justo y con métodos que no dañan el medio ambiente.
          p.mt-3(data-aos="fade-up") La trazabilidad total ofrece ventajas para múltiples acciones a lo largo de la cadena de suministro, más allá de los sistemas de información, entre ellas se resaltan:
      .col-md-5
        img(src="@/assets/curso/tema6/1.svg" data-aos="fade-left")

    .row.mt-5.cont_caja_1
      .col-md-6(style="place-self:center;")
        img(src="@/assets/curso/tema6/2.svg" data-aos="fade-left")
      .col-md-6
        PasosA.color-acento-botones(tipo="n")
          div
            p(data-aos="fade-up") Mecanismo para cumplir con las políticas y normativas locales e internacionales.
          div
            p(data-aos="fade-up") Reducción del riesgo de que entren materiales ilegales o no conformes en las cadenas de suministro.
          div
            p(data-aos="fade-up") Facilitar la coordinación entre las autoridades y los organismos pertinentes.
          div
            p(data-aos="fade-up") Permitir la conciliación automática de lotes y volúmenes disponibles.
          div
            p(data-aos="fade-up") Ofrecer un método de control y seguimiento de las existencias.
          div
            p(data-aos="fade-up") Activar las alertas de incumplimiento en tiempo real.
          div
            p(data-aos="fade-up") Reducir la probabilidad de errores de registro.
          div
            p(data-aos="fade-up") Mejorar la eficacia y la eficiencia.
          div
            p(data-aos="fade-up") Aumentar la transparencia.
          div
            p(data-aos="fade-up") Promover la integridad de la empresa.

    p.mt-4(data-aos="fade-up") En logística, la trazabilidad se refiere a la capacidad de rastrear las mercancías a lo largo de la cadena de distribución sobre la base de un número de lote o de serie. 
    p.mt-3(data-aos="fade-up") Un aspecto fundamental en el reporte y registro de novedad es la definición de los objetivos estratégicos, las metas, los proyectos y los indicadores es un factor determinante para establecer el calendario y el flujo de las cadenas de suministro. Siempre es necesario tener un plan B y C en caso de que la alternativa falle y ofrecer un buen servicio. Para estar informado sobre el inventario de mercancías en almacén, es necesario implementar un sistema de información debido a que ofrecen en tiempo real un estado de entradas y salidas de los productos.
    p.mt-3(data-aos="fade-up") En el reporte y registro de novedades, se utiliza la logística inversa, y a esto se le atribuye cualquier proceso o gestión posterior a la venta del producto, por ejemplo, si el producto es defectuoso, el cliente lo devolvería. La empresa fabricante tendría entonces que organizar el envío del producto defectuoso, probar el producto, desmontarlo, repararlo, reciclarlo o eliminarlo.

    .bloque-texto-a.color-primario.color2.p-4.p-md-5.mt-5.col-md-9.m-auto 
      .row.m-0.align-items-center.justify-content-between
        .col-lg-4.mb-4.mb-lg-0
        .col-lg-8
          .bloque-texto-a__texto.p-4
            p(data-aos="fade-up") La logística se ocupa de los eventos que llevan el producto hacia el cliente. En el caso de la logística inversa, el recurso retrocede al menos un paso en la cadena de suministro. Por ejemplo, la mercancía pasa del cliente al distribuidor o al fabricante.

    p.mt-5(data-aos="fade-up") Un aspecto importante para el éxito de las organizaciones es asegurar que la gestión del proceso logístico esté adecuadamente alineada con la implementación de la dirección estratégica, como requisito previo para obtener resultados en términos de valor añadido, percibido por los clientes internos y externos como condición de eficiencia y competitividad. A continuación, se podrá conocer los 5 principales componentes de gestión de la cadena de suministro: planificar, abastecer, fabricar, entregar y devolver.

    img.mt-5(data-aos="fade-up" src="@/assets/curso/tema6/4.svg")

    p.mt-5(data-aos="fade-up") En resumen, estos son los elementos de la gestión de la cadena de suministro que los líderes tienen en cuenta a la hora de tomar decisiones estratégicas. Por lo tanto, cada componente es vital para tomar cualquier decisión, ya sea en términos de diversificación de productos o vertical en una organización. Con la tendencia actual a la transformación digital, se han tomado muchas iniciativas digitales para la cadena de suministro, lo que puede ser utilizado por la empresa como una ventaja competitiva. A continuación, podrás profundizar de manera esquemática, sobre el monitoreo y recolección de información de mercancías.

    img.mt-5.col-md-8.m-auto(data-aos="fade-up" src="@/assets/curso/tema6/5.svg")




</template>

<script>
export default {
  name: 'Tema6',
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
  background-color: #E7EEFD
.cajon-b:before
  bottom: 76%
.color2:before
  background-color: #34D9C7 !important
.color2
  background: url("../assets/curso/tema6/3.svg")
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
</style>
