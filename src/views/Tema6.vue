<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 6
      h1 Diseño y elaboración de prótesis

    .row
      .col-md-7.mb-4.mb-md-0(style="place-self:center;")
        p(data-aos="fade-up") Es fundamental que el técnico dental interprete y realice  adecuadamente, sobre el modelo de trabajo, la información plasmada en la prescripción clínica hecha por el profesional odontólogo; para ello, deberá identificar apEs fundamental que el técnico dental interprete y realice  adecuadamente, sobre el modelo de trabajo, la información plasmada en la prescripción clínica hecha por el profesional odontólogo; para ello, deberá identificar apropiadamente las superficies protésicas del modelo sobre el cual realizará el dispositivo intraoral solicitado.
        .cajon.color-primario.p-5.mt-5(style="background-color:#C3F1F2;")
          p.mb-0(data-aos="fade-up") Aparato protésico removible que reemplaza artificialmente la totalidad de los dientes en un paciente edéntulo completo de uno o ambos arcos dentales. En el siguiente video, se presenta el procedimiento de fabricación:
      .col-md-5(style="place-self:center;")
        figure
          img(src="@/assets/curso/tema6/1.png" data-aos="fade-left")

    figure.mt-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/maXNNDyV0Eg" title="Introducción al proceso" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    p.mt-5(data-aos="fade-up") Por otro lado, #[strong la prótesis sobre implantes] se trata de las prótesis dentales de arcada completa que se fijan atornilladas o cementadas sobre seis u ocho implantes osteointegrados. En el siguiente video, se presenta el procedimiento de fabricación:

    figure.mt-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/UFooUzfiVb0" title="Elaboración de plato base" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)



</template>

<script>
export default {
  name: 'Tema6',
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
