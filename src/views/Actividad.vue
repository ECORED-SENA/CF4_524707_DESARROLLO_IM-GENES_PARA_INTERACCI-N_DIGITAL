<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno(icono="far fa-question-circle" titulo="Actividad didáctica")
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5
  
      #Actividad                
        <Actividad :cuestionario="cuestionario"/>
  
  </template>

<script>
import Actividad from 'ecored-pkg-fliz/plugin/components/actividad/Actividad.vue'
export default {
  name: 'ActividadDidactica',
  components: {
    Actividad,
  },
  data: () => ({
    cuestionario: {
      tema: 'Microcontroladores y sensores',
      titulo: 'Cuestionario',
      introduccion:
        '<b> Objetivo:</b> Evaluar la comprensión y el uso adecuado de las herramientas básicas en la ventana <em>Board</em> del <em>software</em> EAGLE.',
      barajarPreguntas: true,
      titulo_aprobado: '¡BUEN TRABAJO!',
      titulo_reprobado: 'VUELVA A INTENTARLO.',
      preguntas: [
        {
          id: 1,
          texto:
            '¿Qué implica la creación de contenidos digitales en el contexto actual?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'La reproducción de procesos exclusivamente manuales.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'La eliminación de recursos tecnológicos en educación.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'La integración de conocimientos técnicos, creativos y comunicativos.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto:
                'La sustitución total de medios audiovisuales tradicionales.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 2,
          texto:
            '¿Cuál es uno de los sectores donde se aplica la animación digital?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'La agricultura exclusivamente manual.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'La publicidad, los videojuegos y el cine.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'La minería sin apoyo tecnológico.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'La fabricación artesanal tradicional.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 3,
          texto: '¿Qué caracteriza a la animación digital 2D?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'El uso exclusivo de modelos tridimensionales.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'La simulación física en tiempo real.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'La programación avanzada de motores gráficos.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'La creación de movimiento en un plano bidimensional.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 4,
          texto:
            '¿En qué programas suele desarrollarse la base gráfica de una animación 2D?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Programas de contabilidad financiera digital.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Editores de texto sin funciones gráficas.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Aplicaciones de gestión administrativa básica.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'Programas de diseño como Photoshop, Illustrator y After Effects.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 5,
          texto: '¿Cuál es la función del dibujo a mano alzada en animación?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Eliminar la fase de planificación visual.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Servir como base conceptual y gráfica del proyecto.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Reemplazar completamente el proceso digital.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Limitar la creatividad del diseñador.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 6,
          texto:
            '¿Qué se recomienda al iniciar el diseño de un personaje animado?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Usar fotografías sin modificaciones previas.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Aplicar efectos visuales complejos inicialmente.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Partir de formas geométricas básicas.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Diseñar directamente en tres dimensiones.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 7,
          texto: '¿Qué caracteriza la técnica cuadro a cuadro?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'El ensamblaje digital de piezas reutilizables.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'El dibujo independiente de cada pose del movimiento.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'La animación automática generada por <i>software</i>.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'La eliminación de la secuencia temporal.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 8,
          texto:
            '¿Cuál es una ventaja de la animación por partes tipo marioneta?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Mayor tiempo de producción manual.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Necesidad de redibujar cada fotograma completo.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Imposibilidad de realizar ajustes posteriores.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Optimización del tiempo y reutilización de elementos.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 9,
          texto: '¿Cuál fue el propósito inicial de Photoshop?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'La creación exclusiva de videojuegos tridimensionales.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'El modelado avanzado de entornos virtuales.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'La edición y manipulación fotográfica digital.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'La simulación arquitectónica en tiempo real.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 10,
          texto: '¿Qué permite Photoshop en animación 2D?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'La programación de motores de física avanzada.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'La creación directa de entornos tridimensionales.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'La digitalización y preparación de dibujos en capas.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'La renderización automática de escenas 3D.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 11,
          texto: '¿Qué tipo de gráficos se crean en Illustrator?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Mapas de <i>bits</i> sin escalabilidad.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Gráficos vectoriales escalables sin pérdida de calidad.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Simulaciones físicas complejas en tiempo real.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Modelos tridimensionales con texturas realistas.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 12,
          texto: '¿Cuál es una característica del entorno de After Effects?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Se basa únicamente en dibujo manual.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Funciona sin línea de tiempo ni capas.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'No permite integrar múltiples elementos visuales.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'Organiza elementos en capas dentro de una línea de tiempo',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 13,
          texto: '¿Qué define a la animación 3D?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'La creación exclusiva de gráficos bidimensionales.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'La edición de fotografías estáticas digitales.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'La ilustración manual sin herramientas digitales.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'El movimiento en un espacio tridimensional con ejes X, Y y Z.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 14,
          texto: '¿En qué sectores se aplica ampliamente la animación 3D?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'La escritura literaria tradicional exclusivamente.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'La agricultura sin apoyo tecnológico digital.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Publicidad, videojuegos, cine y arquitectura.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'La contabilidad manual sin digitalización.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 15,
          texto: '¿Cuál es una característica de Autodesk 3DS Max?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Es un editor exclusivo de texto académico.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Se enfoca en modelado, animación y renderizado 3D.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Es una aplicación básica de dibujo manual.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Funciona solo para edición fotográfica simple.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 16,
          texto: '¿Qué distingue a Blender en la industria 3D?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Es un <i>software</i> de código abierto con herramientas integrales.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto:
                'Es un programa exclusivo para edición fotográfica básica.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Es una aplicación limitada únicamente al modelado simple.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Es un sistema cerrado sin funciones de renderizado.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 17,
          texto: '¿Qué comprende la composición digital y los VFX?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'La producción exclusiva de sonido ambiental.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'La impresión física de ilustraciones artísticas.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'La eliminación total de imágenes grabadas.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'La integración y manipulación de imágenes en posproducción.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 18,
          texto: '¿En qué etapa se desarrollan los efectos visuales?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Durante la planeación inicial conceptual.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'En la etapa de posproducción audiovisual.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'En la fase de bocetación manual preliminar.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'En el modelado tridimensional básico inicial.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 19,
          texto: '¿Cuál es una función de Houdini en la industria?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Edición básica de documentos administrativos.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Simulaciones avanzadas y efectos procedurales complejos.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Dibujo manual cuadro a cuadro tradicional.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Gestión contable de proyectos audiovisuales.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 20,
          texto: '¿Qué es la renderización según el glosario?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'La interacción directa entre usuario y <i>hardware.</i>',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'La subdivisión visual de la interfaz gráfica.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'El proceso de generar el resultado final al exportar un proyecto.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'La creación manual de bocetos iniciales.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
      ],
      mensaje_final_aprobado: '¡Excelente! Ha superado la actividad.',
      mensaje_final_reprobado:
        'Le recomendamos volver a revisar el componente formativo e intentar nuevamente la actividad didáctica.',
    },
  }),
}
</script>
s
