<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Anatomía y morfología

    .row
      .col-md-7.mb-4.mb-md-0(style="place-self:center;")
        p(data-aos="fade-up") La anatomía dental es una rama de la odontología que estudia la función, morfología, tejidos y tipos de dientes. Vale la pena tener presente que el técnico dental debe conocer sobre la anatomía dental y que, por medio de los detalles anatómicos, puede definir de qué pieza dental se trata al momento de elaborar una prótesis total.
        .cajon.color-primario.p-5.mt-5(style="background-color:#C3F1F2;")
          p.mb-0(data-aos="fade-up") La morfología dental hace referencia al estudio detallado de cada uno de los dientes, sus estructuras, además de identificar cada pieza dentaria. Durante la elaboración de las prótesis, es indispensable garantizar la funcionalidad en la masticación y deglución de los alimentos. En una persona adulta, hay 32 dientes, es decir, 16 en cada arcada; mientras que los niños sólo tienen 20, 10 por arcada. El ser humano presenta dos tipos de denticiones en su vida: durante su infancia y la de adulto.
      .col-md-5(style="place-self:center;")
        figure
          img(src="@/assets/curso/tema1/1.png" data-aos="fade-left")

    .row.mt-5
      .col-md-4.mb-4.mb-md-0
        figure
          img(src="@/assets/curso/tema1/2.png" data-aos="fade-right")
      .col-md-8
        p(data-aos="fade-up") Durante su infancia y a partir de los seis meses aproximadamente, inicia la erupción de los primeros dientes, y a esta etapa se le llama  dentición temporal. La formación de la anatomía de la boca tiene lugar en las primeras etapas del desarrollo fetal. La boca es importante no solo en el habla y como receptáculo de alimentos, sino que también juega un papel importante en el sistema digestivo. 
        p.mt-4(data-aos="fade-up") Cuando se es adulto, generalmente, se encuentra al ser humano con todos sus dientes en boca, a estos se les llama dentición permanente. Es de aclarar que, entre la infancia y la adolescencia, se presentan ambas denticiones, lo que se llama dentición mixta.
        p.mt-4(data-aos="fade-up") Hay muchos factores que se deben tener en cuenta al observar la morfología del diente; cada diente tiene su propio #[strong "diseño"]. Es necesario visualizar la morfología de cada diente para lograr crear una excelente prótesis. 
        p.mt-4(data-aos="fade-up") El análisis de estética de los dientes maxilares debe ser visto como un todo para realizar prótesis dentales, desde un análisis dentolabial hasta un análisis fonético. Es por ello que cada diente del maxilar tiene características específicas, las cuales se presentan a continuación:

    .tarjeta.tarjeta--azul.mt-5(style="background-color:#D6F8F9;")
      SlyderA(tipo="b")
        .row
          figure
            img(src='@/assets/curso/tema1/3.svg')
        .row
          figure
            img(src='@/assets/curso/tema1/4.svg')
        .row
          figure
            img(src='@/assets/curso/tema1/5.svg')
        .row
          figure
            img(src='@/assets/curso/tema1/6.svg')
        .row
          figure
            img(src='@/assets/curso/tema1/7.svg')
        .row
          figure
            img(src='@/assets/curso/tema1/8.svg')
        .row
          figure
            img(src='@/assets/curso/tema1/9.svg')

    p.mt-5(data-aos="fade-up") Los dientes pueden variar en tamaño, forma y su localización en la mandíbula. Estas diferencias permiten que los dientes trabajen juntos para ayudar a masticar, hablar y sonreír. También ayudan a dar la forma y estructura de la cara. A continuación, se presentan las características de los dientes mandibulares:

    .tarjeta.tarjeta--azul.mt-5(style="background-color:#E5F1F8;")
      SlyderA(tipo="b")
        .row
          figure
            img(src='@/assets/curso/tema1/10.svg')
        .row
          figure
            img(src='@/assets/curso/tema1/11.svg')
        .row
          figure
            img(src='@/assets/curso/tema1/12.svg')
        .row
          figure
            img(src='@/assets/curso/tema1/13.svg')
        .row
          figure
            img(src='@/assets/curso/tema1/14.svg')
        .row
          figure
            img(src='@/assets/curso/tema1/15.svg')
        .row
          figure
            img(src='@/assets/curso/tema1/16.svg')




</template>

<script>
export default {
  name: 'Tema1',
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
.slyder-a__tipo-b
  padding: 2rem
</style>
