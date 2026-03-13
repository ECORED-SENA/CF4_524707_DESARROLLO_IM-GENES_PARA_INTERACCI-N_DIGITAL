<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 3
      h1 Composición digital y VFX

    
    p.mb-3.mt-5(data-aos="fade-left") La composición digital y los efectos visuales (<i>Visual Effects</i> – VFX) comprenden el conjunto de técnicas empleadas para crear, integrar o manipular imágenes previamente grabadas. Estos procesos se desarrollan en la etapa de posproducción de un proyecto audiovisual y permiten ampliar, transformar o enriquecer el material original conforme a las necesidades narrativas y estéticas.
    
    .row.mb-5
      .col-lg-5.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema3/1.png", data-aos="zoom-in")
      .col-lg-7        
        .row.mt-3.align-items-start.mb-10.bg-color-4(data-aos="fade-left")  
            p.p-5(data-aos="fade-left") Su aplicación es frecuente en la industria cinematográfica; sin embargo, también se utilizan en videojuegos, televisión y comerciales publicitarios. En todos los casos, la composición digital busca integrar múltiples elementos (video, imágenes generadas por computador, gráficos, partículas o fondos digitales) en una sola escena coherente.


    .row.mt-5
      .col-lg-7
        .row.align-items-start.mb-3(data-aos="fade-left")
          .col-lg
          p.mb-0 Para la producción de composiciones digitales o VFX se emplea una variedad de programas especializados. Algunos flujos de trabajo combinan <b>Photoshop</b> para la creación de montajes o elementos independientes que posteriormente se integran en programas como <b>After Effects</b>, ampliamente utilizado en televisión, videoclips y producciones audiovisuales de mediana complejidad.
        .row.mt-3.align-items-start.mb-10.bg-color-4(data-aos="fade-left")  
            p.p-5(data-aos="fade-left") No obstante, en la industria cinematográfica se requieren herramientas con mayores capacidades técnicas y estándares de calidad más exigentes. En este contexto, destaca el <i>software</i> <b>Houdini</b>, reconocido por su potencia en simulaciones avanzadas, efectos procedurales y dinámicas complejas.
      .col-lg-5.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema3/2.png", data-aos="zoom-in")

    p.mb-3.mt-5.text-center(data-aos="fade-left") A continuación, se sintetizan las herramientas más relevantes en composición digital y VFX:


    .container.tarjeta.tarjeta--blanca.p-4.p-md-5
      .row.justify-content-center.align-items-stretch
        .col-sm-6.col-lg-3.mb-4.mb-lg-0
          .tarjeta--boton.color-primario.p-4.h-100
            .row.justify-content-center.mb-3
              .col-7
                figure
                  img(src='@/assets/curso/tema3/tarjeta1_1.svg', alt='')

            h3.text-center Photoshop
            p Creación de elementos gráficos, retoque y montaje de imágenes para integración posterior.

        .col-sm-6.col-lg-3.mb-4.mb-lg-0
          .tarjeta--boton.color-secundario.p-4.h-100
            .row.justify-content-center.mb-3
              .col-7
                figure
                  img(src='@/assets/curso/tema3/tarjeta1_2.svg', alt='')

            h3.text-center After Effects
            p Composición digital, animación y efectos visuales para televisión, videoclips y proyectos audiovisuales.

        .col-sm-6.col-lg-3.mb-4.mb-sm-0
          .tarjeta--boton.color-acento-contenido.text-white--hover.p-4.h-100
            .row.justify-content-center.mb-3
              .col-7
                figure
                  img(src='@/assets/curso/tema3/tarjeta1_3.svg', alt='')

            h3.text-center Houdini
            p Simulaciones avanzadas y efectos procedurales para cine de alta complejidad.

    p.mb-3.mt-5(data-aos="fade-left") En síntesis, la composición digital y los VFX amplían las posibilidades creativas del lenguaje audiovisual, permitiendo construir escenas que combinan realidad y elementos digitales con altos niveles de integración técnica y artística.



</template>

<script>
export default {
  name: 'Tema3',
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
