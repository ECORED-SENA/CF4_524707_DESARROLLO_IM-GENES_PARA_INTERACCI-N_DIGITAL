<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    p.mb-3 La creación de contenidos digitales implica la integración de conocimientos técnicos, creativos y comunicativos que permiten transformar ideas en productos interactivos y audiovisuales. En este proceso, la combinación de herramientas tecnológicas y fundamentos conceptuales favorece el desarrollo de propuestas innovadoras que responden a las necesidades actuales de los entornos educativos, comunicativos y productivos.

        .bloque-texto-g.bloque-texto-g--inverso.color-acento-contenido.p-3.p-sm-4.p-md-5.mb-3
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/intro/1.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 El avance constante de las tecnologías digitales ha ampliado las posibilidades de producción, facilitando la incorporación de recursos gráficos, animaciones y efectos visuales que enriquecen la experiencia del usuario. Estas transformaciones han generado nuevos escenarios de aprendizaje y trabajo, donde la creatividad y la planeación estratégica se convierten en elementos fundamentales para la construcción de contenidos de calidad.
        
        p.mb-3 En este contexto, comprender los principios, herramientas y metodologías asociadas a la integración de contenidos digitales permite fortalecer competencias orientadas al diseño, producción y adaptación de materiales. Esto contribuye al desarrollo de soluciones comunicativas pertinentes, alineadas con las dinámicas tecnológicas y las demandas del entorno actual.


</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
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

<style lang="sass"></style>
