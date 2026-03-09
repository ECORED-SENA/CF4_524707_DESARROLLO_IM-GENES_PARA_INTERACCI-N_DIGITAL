<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
  
    .row.mb-5
      .col-12.ps-3(style="border-left: 10px solid #39A900;") 
        h3.mb-1 Generación de códigos de <em>software</em> con inteligencia artificial 
        p.mb-0 
          | Síntesis: 
          
          | Desarrollo e integración de la animación

    
    p.mt-5 A continuación, se presenta a manera de síntesis, un esquema que articula los elementos principales abordados en el desarrollo del componente formativo.




    .row.justify-content-center
      .col-lg-10.mb-5.bgs.p-4.brad
        figure
          img(src="@/assets/curso/sintesis.svg", alt="Síntesis sobre desarrollo e integración de la animación que organiza categorías como creación de contenidos digitales, animación digital 2D, estrategias de animación 2D, herramientas 2D, animación 3D y <i>software</i> de animación 3D, con subtemas relacionados con técnicas, aplicaciones, procesos y programas especializados.")
      .col-auto
        a.anexo.mb-5(:href="obtenerLink('/downloads/Sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/bullets/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis




</template>

<script>
export default {
  name: 'Sintesis',
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
