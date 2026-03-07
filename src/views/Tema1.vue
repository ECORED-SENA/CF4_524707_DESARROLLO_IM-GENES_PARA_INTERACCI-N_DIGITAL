<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 1
      h1 Animación Digital 2D



    p.mb-2(data-aos="fade-left") La animación digital 2D ha experimentado un crecimiento constante, lo que ha dado lugar a la aparición de diversos programas especializados en la creación de movimiento. Estas herramientas permiten dar vida tanto a objetos y textos (como los empleados en infografías) como a personajes de caricatura.
              
    .row.justify-content-center.align-items-center.mb-2
      .col-lg-10
        .p-lg-5(data-aos="fade-right")
          .row.justify-content-center.align-items-center
            .col-lg-7.mb-4.mb-lg-0.bg-color-1.p-5
              p.mb-0 Generalmente, la base de las animaciones se desarrolla en programas de diseño gráfico, donde los artistas construyen los elementos que posteriormente serán animados. Para la producción y desarrollo de estos recursos se emplean aplicaciones de la #[i suite] de Adobe, entre ellas Photoshop, Illustrator y After Effects, ampliamente utilizadas en la industria creativa por su integración y versatilidad.
            .col-lg-5
              figure
                img(src='@/assets/curso/tema1/1.svg', alt='')   
        
    p.mb-3(data-aos="fade-left") La animación digital 2D ha experimentado un crecimiento constante, lo que ha dado lugar a la aparición de diversos programas especializados en la creación de movimiento. Estas herramientas permiten dar vida tanto a objetos y textos (como los empleados en infografías) como a personajes de caricatura.


    .row.justify-content-center.align-items-center.mb-4
      .col-lg-12(data-aos="flip-up")
        .bg-color-2.p-4
          .row.justify-content-center.align-items-center
            .col
              p.mb-0 Aunque existen técnicas de animación menos difundidas, cualquier procedimiento que implique producir imágenes y organizarlas de forma secuencial puede emplearse para generar movimiento. En este apartado se aborda el proceso desde la representación manual de objetos hasta su vectorización mediante herramientas digitales.
            .col-auto
              figure
                img(src='@/assets/curso/tema1/icon-text.svg', alt='', style="width: 80px")


    //- Inicio Tema1.1
    .row.mt-5
        #t_1_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
          h2 1.1 Dibujo a mano alzada

    p.mb-3(data-aos="fade-left") El dibujo a mano alzada constituye la base conceptual y gráfica de un proyecto de animación. Permite representar objetos reales, animales o ideas abstractas que luego se desarrollarán en un entorno digital. A partir de bocetos en papel es posible definir la idea principal, establecer la secuencia de acciones y planificar los pasos que orientarán la construcción de una propuesta más elaborada.

    .row.justify-content-center.align-items-center.mb-2
      .col-lg-12
        .p-lg-5(data-aos="fade-right")
          .row.justify-content-center.align-items-center
            .col-lg-4
              figure
                img(src='@/assets/curso/tema1/2.svg', alt='')           
            .col-lg-8.mb-4.mb-lg-0.bg-color-1.p-5
              p.mb-0 Para iniciar el proceso de diseño de un personaje se recomienda partir de formas geométricas básicas. Estas estructuras iniciales facilitan la proporción y la coherencia anatómica, especialmente cuando se pretende animar un ciclo de caminado. En este tipo de animación, el personaje adopta una pose diferente en cada dibujo, de modo que la secuencia completa represente el desplazamiento alternado de las piernas y genere la sensación de avance continuo.
            


    .row.justify-content-center.align-items-center.mb-4
      .col-lg-12(data-aos="flip-up")
        .bg-color-2.p-4
          .row.justify-content-center.align-items-center
            .col-auto
              figure
                img(src='@/assets/curso/tema1/icon-text.svg', alt='', style="width: 80px")
            .col
              p.mb-0 Otra estrategia consiste en diseñar el personaje por partes, dibujando cada miembro de forma independiente. Posteriormente, estos elementos se ensamblan digitalmente para animarlos como si se tratara de una marioneta. Esta técnica optimiza tiempos de producción y permite reutilizar componentes sin necesidad de redibujar cada cuadro. A continuación, se sintetizan las dos estrategias principales de trabajo en la etapa inicial de animación:




    //- Fin Tema1.1



</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({
    mostrarIndicadorTarjetaAudio: true,
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
