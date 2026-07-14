<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
      .titulo-principal.color-acento-contenido
        .titulo-principal__numero
          span 1
        h1 Fundamentos y preparación de la negociación
      .bloque-texto-g.bloque-texto-g--inverso.color-secundario.p-3.p-sm-4.p-md-5
        .bloque-texto-g__img(
          :style="{'background-image': `url(${require_src('@/assets/curso/temas/t1/img01.jpg')})`}"
        )
        .bloque-texto-g__texto.p-4
          p.mb-0(data-aos="fade-down") La negociación se considera una estrategia poderosa en la gestión organizacional, ya que permite encontrar puntos de acuerdo, generar unidad en contextos divergentes y gestionar conflictos, alcanzando beneficios compartidos bajo enfoques ganar-ganar. No obstante, resulta fundamental contextualizar el conflicto como el origen que da lugar al proceso de negociación.
      separador
      #t_1_1.titulo-segundo.color-acento-contenido(data-aos="flip-up")
        h2 1.1 Definición de conflicto
      .row.justify-content-center.mb-4
        .col.col-lg-3.col-8.col-md-6.order-lg-1.order-1.mb-lg-0.mb-3
          figure
            img(src='@/assets/curso/temas/t1/img02.svg', alt='Imagen decorativa')
        .col.col-lg-9.col-12.order-lg-2.order-2
          p.mb-4(data-aos="fade-down") El conflicto se considera una contradicción o antagonismo que se presenta entre una o más personas debido a percepciones, valores o intereses opuestos. En la organización por su parte el conflicto es innato, surge de la inevitable interacción humana entre miembros de diferentes equipos, áreas o departamentos generada por las metas, recursos limitados o roles mal definidos; por esto debe ser tenido en cuenta en la gestión organizacional. Su finalidad es mejorar las relaciones entre los integrantes de la organización, así como la consecución de sus logros.
          p.mb-0(data-aos="fade-down")  El conflicto atraviesa distintas etapas:
      .row.justify-content-center.align-items-center.mb-4(data-aos="flip-up")
        SlyderF.color-acento-botones(columnas="col-lg-6 col-xl-4")
          .tarjeta.tarjeta--bg01.p-4
            .row.justify-content-center.mb-3
              .col-lg-6.col-sm-4.col-6
                img(src='@/assets/curso/temas/t1/img03.svg' alt='AvatarTop')
            h4.text-center Oposición o surgimiento
            p Aparece una diferencia de intereses, percepciones o necesidades, generalmente provocada por fallas en la comunicación o recursos limitados.
          .tarjeta.tarjeta--bg01.p-4
            .row.justify-content-center.mb-3
              .col-lg-6.col-sm-4.col-6
                img(src='@/assets/curso/temas/t1/img04.svg' alt='AvatarTop')
            h4.text-center Conocimiento y personalización
            p Las partes reconocen la existencia del conflicto y lo asumen de manera consciente, vinculándolo a intereses personales o grupales.
          .tarjeta.tarjeta--bg01.p-4
            .row.justify-content-center.mb-3
              .col-lg-6.col-sm-4.col-6
                img(src='@/assets/curso/temas/t1/img05.svg' alt='AvatarTop')
            h4.text-center Intenciones
            p Cada parte define su postura y determina cómo actuará frente al conflicto, ya sea de forma colaborativa, competitiva o evasiva.
          .tarjeta.tarjeta--bg01.p-4
            .row.justify-content-center.mb-3
              .col-lg-6.col-sm-4.col-6
                img(src='@/assets/curso/temas/t1/img06.svg' alt='AvatarTop')
            h4.text-center Comportamiento
            p El conflicto se expresa mediante acciones visibles, como discusiones, desacuerdos abiertos o conductas confrontativas.
          .tarjeta.tarjeta--bg01.p-4
            .row.justify-content-center.mb-3
              .col-lg-6.col-sm-4.col-6
                img(src='@/assets/curso/temas/t1/img07.svg' alt='AvatarTop')
            h4.text-center Desenlace
            p Se alcanza un resultado que puede ser funcional, cuando contribuye al aprendizaje y mejora organizacional, o disfuncional, si genera efectos negativos.
      p.mb-4(data-aos="fade-down") La siguiente imagen resume estas fases y cómo se presentan en un conflicto:
      .row.justify-content-center.mb-lg-4(data-aos="flip-up")
        .col-lg-10.col-12
          .titulo-sexto.color-acento-contenido
            h5 Figura 1.
            span Proceso del conflicto
        .row.justify-content-center
          .col-10
            figure.desktop
              img(src='@/assets/curso/temas/t1/img08.svg', alt='Figura 1 que representa las etapas del conflicto organizacional, iniciando con la oposición potencial como situación latente que genera malestar, seguida del conocimiento y la personalización donde el conflicto se hace manifiesto, continuando con el comportamiento en el que se expresan las tensiones, y finalizando con los resultados, que pueden derivar en consecuencias constructivas o en conflicto violento.')
        .col-12.mb.sm-4
          figure.movil
            img(src='@/assets/curso/temas/t1/img09.svg', alt='Figura 1 que representa las etapas del conflicto organizacional, iniciando con la oposición potencial como situación latente que genera malestar, seguida del conocimiento y la personalización donde el conflicto se hace manifiesto, continuando con el comportamiento en el que se expresan las tensiones, y finalizando con los resultados, que pueden derivar en consecuencias constructivas o en conflicto violento.')
      p.mb-4(data-aos="fade-down") En el proceso del conflicto se identifican distintos niveles, según las personas o grupos involucrados:
      .bloque-texto-f.color-acento-contenido.pt-4.px-5.mb-5
        h4.text-regular.bloque-texto-f__texto La clave no es evitar el conflicto, sino gestionarlo para mejorar el funcionamiento de la organización y fomentar el crecimiento. 
        .bloque-texto-f__autor.mb-3
          h3.mb-0 The graphic designer
        .bloque-texto-f__avatar
          .bloque-texto-f__avatar__img
            img(src='@/assets/curso/temas/t1/img10.svg', alt='Imagen decorativa')
        
      separador
      #t_1_2.titulo-segundo.color-acento-contenido(data-aos="flip-up")
        h2 1.2 Definición de negociación
      separador
      #t_1_3.titulo-segundo.color-acento-contenido(data-aos="flip-up")
        h2 1.3 Elementos y características de la negociación
      separador
      #t_1_4.titulo-segundo.color-acento-contenido(data-aos="flip-up")
        h2 1.4 Estilos de negociación
      separador
      #t_1_5.titulo-segundo.color-acento-contenido(data-aos="flip-up")
        h2 1.5 Fases de la negociación
      separador
      #t_1_6.titulo-segundo.color-acento-contenido(data-aos="flip-up")
        h2 1.6 Tipos de negociación
      separador
      #t_1_7.titulo-segundo.color-acento-contenido(data-aos="flip-up")
        h2 1.7 Técnicas de negociación
        

  </template>

<script>
export default {
  name: 'Tema1',
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
