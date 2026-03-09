<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 2
      h1 Animación 3D
    

    //- Inicio Tema1.2

    .row.mb-10
      
      .col-lg-7
        .row.align-items-start.mb-3(data-aos="fade-left")
          .col-lg
          p.mb-0 La animación 3D consiste en dar movimiento a objetos y personajes dentro de un espacio tridimensional, lo que permite que puedan desplazarse y rotar en los ejes X, Y y Z. Para su desarrollo se emplean softwares especializados que posibilitan el modelado y la escultura digital de formas complejas.
        .row.mt-3.align-items-start.mb-10.bg-color-4(data-aos="fade-left")  
            p.p-4(data-aos="fade-left") Los animadores y diseñadores crean entornos, objetos o personajes con características propias para construir narrativas coherentes y atractivas. Este tipo de animación tiene amplia aplicación en sectores como la publicidad, los videojuegos, el cine, la arquitectura y la realidad virtual, debido a su capacidad para generar escenas con alto nivel de detalle y realismo.
      .col-lg-5.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema2/1.png", data-aos="zoom-in")

    p.mb-3.mt-5(data-aos="fade-left") A continuación, se presentan algunos de los programas más utilizados en la industria para la producción de animación 3D:
    


    .container.tarjeta.tarjeta--blanca.p-4.p-md-5
      .row
        .col-sm-6.col-lg-3.mb-4.mb-lg-0
          .tarjeta--boton.color-primario.p-4.h-100
            .row.justify-content-center.mb-3
              .col-7
                figure
                  img(src='@/assets/curso/tema2/tarjeta1_1.svg', alt='')

            h3.text-center Autodesk 3DS Max
            p Enfocado en modelado, animación y renderizado. Ampliamente utilizado en videojuegos, arquitectura y producción audiovisual.

        .col-sm-6.col-lg-3.mb-4.mb-lg-0
          .tarjeta--boton.color-secundario.p-4.h-100
            .row.justify-content-center.mb-3
              .col-7
                figure
                  img(src='@/assets/curso/tema2/tarjeta1_2.svg', alt='')

            h3.text-center Autodesk Maya
            p Especializado en animación de personajes y efectos visuales para cine y televisión.

        .col-sm-6.col-lg-3.mb-4.mb-sm-0
          .tarjeta--boton.color-acento-contenido.text-white--hover.p-4.h-100
            .row.justify-content-center.mb-3
              .col-7
                figure
                  img(src='@/assets/curso/tema2/tarjeta1_3.svg', alt='')

            h3.text-center Blender
            p <i>Software</i> de código abierto con herramientas integrales para modelado, animación, simulación y renderizado.

        .col-sm-6.col-lg-3
          .tarjeta--boton.color-acento-botones.p-4.h-100
            .row.justify-content-center.mb-3
              .col-7
                figure
                  img(src='@/assets/curso/tema2/tarjeta1_4.svg', alt='')

            h3.text-center Cinema 4D
            p Destacado en gráficos en movimiento y diseño para publicidad y contenidos audiovisuales.


    p.mb-3.mt-5(data-aos="fade-left") Especialmente, <b>Autodesk 3DS Max</b>, desarrollado por Autodesk, es uno de los programas más empleados en la industria de los videojuegos, los anuncios televisivos, la visualización arquitectónica y el cine, debido a su potencia en modelado y animación avanzada.


    //- Fin Tema1.2


</template>

<script>
export default {
  name: 'Tema2',
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
