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

      .container.tarjeta.tarjeta--blanca.p-4.p-md-5
        TabsC.color-acento-contenido.mt-1
          .py-3.py-md-4(titulo="Secuencia cuadro a cuadro")
            .row
              .col-md-6
                figure
                  img(src='@/assets/curso/tema1/pestana1_1.png', alt='')
              .col-md-6.mb-4.mb-md-0
                h4 Secuencia cuadro a cuadro
                p Cada pose se dibuja de manera independiente. Permite mayor control del movimiento y resultados más orgánicos. Requiere mayor tiempo de producción.                    

          .py-3.py-md-4(titulo="Animación por partes (tipo marioneta)")
            .row
              .col-md-6.mb-4.mb-md-0
                figure
                  img(src='@/assets/curso/tema1/pestana1_2.png', alt='')
              .col-md-6
                h4 Animación por partes (tipo marioneta)
                p El personaje se diseña por segmentos (brazos, piernas, torso). Los elementos se articulan digitalmente. Optimiza el tiempo y facilita ajustes posteriores.


    p.mb-3(data-aos="fade-left") Estas estrategias pueden combinarse según las necesidades narrativas, el estilo gráfico y los tiempos de producción definidos para el proyecto.

    //- Fin Tema1.1

    //- Inicio Tema1.2
    .row.mt-5
        #t_1_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
          h2 1.2 Photoshop


    .row.mb-10
      .col-lg-5.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/3.png", data-aos="zoom-in")
      .col-lg-7
        .row.align-items-start.mb-3(data-aos="fade-left")
          .col-lg
          p.mb-0 Photoshop surgió como un programa orientado a la edición y manipulación fotográfica; sin embargo, en la actualidad se emplea en múltiples procesos artísticos que incluyen dibujo digital, ilustración y animación mediante diversas técnicas, como la <i>rotoscopia</i>. Su versatilidad lo ha consolidado como una herramienta fundamental en la industria del diseño y la animación digital.
        .row.mt-3.align-items-start.mb-10.bg-color-4(data-aos="fade-left")  
            p.p-4(data-aos="fade-left") En el contexto de la animación 2D, Photoshop permite digitalizar dibujos realizados a mano alzada y prepararlos para su posterior integración en programas como After Effects.


    p.mb-3(data-aos="fade-left") El siguiente recurso orienta el proceso de preparación de personajes en Photoshop mediante la segmentación en capas, permitiendo organizar cada parte del cuerpo de forma independiente para facilitar su posterior animación en programas especializados como After Effects.
    
    //- Fin Tema1.2

    //- Inicio Tema1.3
    .row.mt-5
        #t_1_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
          h2 1.3 Illustrator


    .row.mb-10
      .col-lg-7        
        .row.mt-3.align-items-start.mb-10.bg-color-1(data-aos="fade-left")  
            p.p-4(data-aos="fade-left") Illustrator es un editor de gráficos vectoriales ampliamente utilizado en el diseño gráfico, la ilustración digital y los procesos de animación 2D. Su entorno de trabajo se asemeja a un taller artístico digital en el que, a partir de una “Mesa de trabajo”, se crea un “Documento” adaptable a las necesidades del usuario. Esta estructura permite construir gráficos escalables sin pérdida de calidad, lo que resulta especialmente útil en la vectorización de personajes.
      .col-lg-5.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/4.png", data-aos="zoom-in")

    p.mb-3(data-aos="fade-left") El siguiente video presenta el proceso de vectorización y preparación de un personaje en Illustrator, explicando paso a paso la configuración del espacio de trabajo, el uso de herramientas de trazado y la organización de capas, hasta su exportación para la animación digital en programas especializados.
    
    //- Fin Tema1.3



    //- Inicio Tema1.4
    .row.mt-5
        #t_1_4.titulo-segundo.color-acento-contenido(data-aos="fade-right")
          h2 1.4 After Effects
    p.mb-3(data-aos="fade-left") After Effects es un programa especializado en animación, composición y efectos digitales, utilizado en la producción cinematográfica, el diseño infográfico y la televisión, entre otros ámbitos. Su entorno de trabajo se basa en una línea de tiempo, donde los elementos se organizan por capas dentro de una composición. Esta estructura lo convierte en una herramienta versátil para proyectos audiovisuales de diversa complejidad. A continuación, se describen los pasos para animar el ciclo de caminado del personaje previamente diseñado, digitalizado o vectorizado.    
    .row.mb-12
      .col-lg-5.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/3.png", data-aos="zoom-in")

    //- Fin Tema1.4

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
