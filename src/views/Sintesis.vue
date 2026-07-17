<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    p El componente formativo desarrolla los fundamentos de la negociación, entendida como un proceso que surge del conflicto y permite gestionar diferencias para alcanzar acuerdos, abordando sus elementos, características, estilos, tipos y técnicas. Posteriormente, se profundiza en los fundamentos del mercadeo, incluyendo su definición, elementos, características y clasificación, así como la segmentación con enfoque en el cliente, para finalmente integrar el proceso de venta.
    p Desde esta perspectiva, comprender el origen de la negociación permite reconocerla como una estrategia que facilita el tránsito de la divergencia al acuerdo, siempre que las condiciones, el contexto y los criterios de las partes involucradas lo permitan.
    .row.justify-content-center
      .col-12.mb-5.bgs.p-4.brad
        figure
          img(src="@/assets/curso/sintesis.svg", alt="En la síntesis se presenta un mapa conceptual que organiza los fundamentos de la negociación y el mercadeo en dos ejes principales. En el primero, se aborda el conflicto como origen de las diferencias y la negociación como proceso de acuerdo, integrando sus elementos, características, estilos, fases, tipos y técnicas. En el segundo eje, se desarrollan los fundamentos del mercadeo, incluyendo su definición, los tipos de mercado, la segmentación, el cliente actual y el proceso de venta. En conjunto, el mapa relaciona estos componentes para comprender la gestión de acuerdos y la dinámica del mercado en contextos organizacionales y comerciales.")
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
