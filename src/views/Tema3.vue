<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Tecnologías mixtas digital y analógica

    .row
      .col-md-5.mb-4.mb-md-0(style="place-self:center;")
        figure
          img(src="@/assets/curso/tema3/1.png" data-aos="fade-right")
      .col-md-7(style="place-self:center;")
        .row
          .col-auto
            figure
              img(src="@/assets/curso/tema3/2.svg" data-aos="fade-right")
          .col
            p(data-aos="fade-up") Cada dispositivo intraoral puede ser confeccionado teniendo en cuenta las indicaciones de  la orden de trabajo y la tecnología con la que cuente el laboratorio dental; sin embargo, en los procesos de elaboración de las prótesis totales, se debe tener en cuenta que cada caso clínico tiene unos protocolos de elaboración distintos.
        .cajon.color-primario.p-4.mt-5(style="background-color:#C3F1F2;")
          p.mb-0(data-aos="fade-up") Para utilizar herramientas digitales, se requiere una preparación similar a la que se hace en la confección analógica, con la diferencia de que debe apoyarse en un software, un escáner y una fresadora para su realización. 



</template>

<script>
export default {
  name: 'Tema3',
  components: {},
  data: () => ({
    indicadorTarjetaSlide: true,
    indicadorTarjetaFlip: true,
  }),
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
.cajon.color-primario:before
  background-color: #13C6CC
</style>
