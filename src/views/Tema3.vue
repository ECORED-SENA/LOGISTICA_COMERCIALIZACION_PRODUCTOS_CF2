<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal
      .titulo-principal__numero
        span 3
      h1 Programación de tiempos en la cadena de suministro

    .cajon-b.color-primario.p-3
      p(data-aos="fade-up") El plazo de entrega o período de entrega, se refiere al tiempo que transcurre desde que se hace un pedido a un proveedor, hasta que la mercancía se entrega desde el distribuidor al comprador. El funcionamiento de este criterio es necesario para la organización de todos los procesos a lo largo de la cadena de suministro. Desde un punto de vista teórico, el tiempo de ciclo de los pedidos se refiere al tiempo que transcurre desde que se realiza un pedido a un proveedor hasta que se entrega al cliente.

    .bloque-texto-a.color-primario.color2.p-4.p-md-5.mt-2.col-md-9.m-auto 
      .row.m-0.align-items-center.justify-content-between
        .col-lg-4.mb-4.mb-lg-0
        .col-lg-8
          .bloque-texto-a__texto.p-4
            p(data-aos="fade-up") #[strong Lo que compra:] desde que el cliente hace el pedido hasta que el producto llega al almacén.
            p.mt-3(data-aos="fade-up") #[strong Lo que vende:] desde que el cliente hace el pedido hasta que el producto llega al almacén del cliente.

    p.mt-5(data-aos="fade-up") El #[em lead time], aplica para los departamentos de ventas, compras, producción y distribución y es uno de los indicadores clave o críticos para poder hacer esas actividades correctamente. A continuación, se podrá conocer el #[em lead time] del departamento de producción.

    ImagenInfografica.color-secundario.mt-5
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/tema3/2.svg', alt='')
      .tarjeta.color-acento-botones.p-3.text-center(x="36%" y="66%" numero="" style="background-color:#CFDDFC;")
        .h4.mb-2 Producción
        p Necesita conocer el #[em lead time] de los procesos para poder dar tiempos de ventas con respecto a las fechas de entrega; si está en distribución necesita conocer todos los #[em lead time] para poder saber en qué momento van a llegar los productos a la empresa.
      .tarjeta.color-acento-botones.p-3.text-center(x="62%" y="20%" numero="" style="background-color:#CFDDFC;")
        .h4.mb-2 Compras
        p Necesita conocer el #[em lead time] de los proveedores para coordinar con producción respecto al tiempo o el momento en que van a llegar los materiales o los productos que se necesitan para hacer la producción.
      .tarjeta.color-acento-botones.p-3.text-center(x="79%" y="60%" numero="" style="background-color:#CFDDFC;")
        .h4.mb-2 El vendedor
        p Tiene conocimiento del #[em lead time] del departamento de producción para cumplir con tiempos de entrega con los clientes.
      .tarjeta.color-acento-botones.p-3.text-center(x="19%" y="30%" numero="" style="background-color:#CFDDFC;")
        .h4.mb-2 Pedido
        p

    p.mt-5(data-aos="fade-up") Para calcular el #[em lead time], se debe tener en cuenta, si se tiene un número de pedidos, pueden ser productos o mercancías con diferentes fechas de entrega, lo único que se obtiene son los días transcurridos para la entrega y se contabilizan según el calendario. Es decir:

    .col-lg-8.m-auto
      .cajon.color-secundario.p-4.mb-4
        .h5.text-center #[em lead time] = fecha de entrega – fecha de pedido
        img.mt-3(src='@/assets/curso/tema3/3.svg', alt='' data-aos="fade-up")

    p.mt-5(data-aos="fade-up") En la programación de los tiempos de la cadena de suministros, se debe tener en cuenta la correcta distribución que depende de una red de abastecimiento, donde se observan los diferentes pedidos del cliente con todos los tiempos de ciclo de los productos, teniendo en cuenta los materiales que se utilizan de las partes de producción, los tiempos de ciclo de compras; es por ello, que aunque el cálculo del indicador es muy sencillo, para la planeación es fundamental conocer todos los #[em lead time] y de esta forma saber exactamente fechas de entrega. A continuación, podrá conocer el diagrama de #[em lead time] a lo largo de la cadena de suministro.

    img.mt-5(src='@/assets/curso/tema3/4.svg', alt='' data-aos="fade-up")

    .row.mt-5
      .col-md-7
        .cajon-b.color-primario.p-3.cajon_1
          p(data-aos="fade-up") Tomando el ejemplo del diagrama mostrado, para un cliente de la cadena de suministro, el #[em lead time] será el acumulado del resto: el de los proveedores de materias primas, el de la fábrica que tiene que producirlo y el del centro de distribución que lo enviará. Por eso, aunque el cálculo del #[em lead time] sea sencillo, es importante conocer su desglose en profundidad para una correcta organización de las operaciones. Además, hay que tener en cuenta otros cambios adicionales, como que el proveedor solo reconozca las demandas en un día concreto de la semana (si solo acepta pedidos los martes y los jueves, el retraso para un pedido realizado el lunes será de un día).
          p.mt-3(data-aos="fade-up") Los tiempos de aprovisionamiento se miden con mayor precisión en función del historial de demanda y entregas de la organización. Se trata de un punto de partida más fiable que las promesas oficiales de los proveedores, porque en la realidad suele haber variaciones.
      .col-md-5
        img(src="@/assets/curso/tema3/5.svg" data-aos="fade-left")

    .col-lg-11.m-auto.mt-5
      .cajon.color-secundario.p-5.mb-4
        p.text-center(data-aos="fade-up") El #[em lead time] es un componente fundamental gracias a la probabilidad de obtener una mayor flexibilidad y capacidad de contestación, en el caso en el que se logre disminuir correctamente y  se tenga una idónea administración de la cadena de abastecimiento logístico. Es decir, al tener entendimiento de todos los lapsos que se generan en los procesos productivos y de repartición de la organización, se podrán optimizar los mismos, de forma fácil y planear el inventario con los menores errores posibles.
        img.mt-3.col-lg-8.m-auto(src='@/assets/curso/tema3/6.svg', alt='' data-aos="fade-up")



</template>

<script>
export default {
  name: 'Tema3',
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
  bottom: 20%
.cajon_1:before
  bottom: 50%
.color2:before
  background-color: #34D9C7 !important
.color2
  background: url("../assets/curso/tema3/1.svg")
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
.cajon.color-secundario
    background-color: #DBF5F2
.cajon.color-secundario:before
    background-color: #34D9C7
</style>
