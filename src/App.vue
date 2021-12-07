<template lang="pug">
#app.app
  Header
  .contenedor-principal
    AsideMenu
    section.seccion-principal(:class="{'seccion-principal--barra-avance-open' : !menuState}")
      router-view
  BarraAvance
  Accesibilidad
</template>

<script>
export default {
  name: 'App',
  data: () => ({
    menuOpen: false,
  }),
  computed: {
    menuState() {
      return this.$store.getters.isMenuOpen
    },
  },
  mounted() {
    this.$aos.init({
      offset: 100,
    })
  },
}
</script>

<style lang="sass">
.titulo-principal__numero
  background-color: #FF5151
.curso-main-container > .container
    overflow-x: inherit !important
.titulo-segundo:after
  border-left-color: #5C22C3 !important
.row
  margin-left: 0px !important
  margin-right: 0px !important
.titulo-principal__numero
  background-color: #34D9C7
.banner-interno__titulo__icono i
    color: #11263f
</style>
