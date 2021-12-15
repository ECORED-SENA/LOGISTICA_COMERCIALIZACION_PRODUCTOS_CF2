<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    p(data-aos="fade-up") Para el desarrollo de la economía de una zona o territorio, es imprescindible potenciar las actividades de logística y transporte, ya que son componentes claves de la competitividad. Asimismo, para aumentar su competitividad, el sector industrial y productivo, se ven obligados fundamentalmente a minimizar precios de la logística y el transporte que gravan el costo de sus productos. En el siguiente recurso de aprendizaje podrá conocer sobre el transporte y la gestión de logística.
    figure.mt-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/e4znUHgX9LY" title="" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>
<style lang="sass"></style>
