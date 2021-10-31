<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Administración deportiva
    .row.mb-5.slideInUp
      .col-lg-7
        p.mb-text-bold-text-blue  El deporte aparte de ser una disciplina es también un sector, que año tras año cobra mayor importancia por su alta demanda e impacto en la salud, bienestar, educación y aportes en el desarrollo social y económico.
        p.mb-3  Al incremento creciente de la demanda de programas deportivos le surge la necesidad de múltiples proyectos y organizaciones que den respuesta a una oferta presentada por medio de servicios, programas de fomento y promoción de la actividad física, deporte y recreación.
        p.mb-3  Para que estas organizaciones sean exitosas, alcancen sus metas y puedan satisfacer las necesidades de sus clientes es indispensable contar con una administración eficiente.
        p.mb-3  Históricamente se han establecido mecanismos para administrar y gobernar en los diferentes ámbitos en los que el ser humano ha estado presente, pero solo hasta el Siglo XX nace la administración como ciencia, en donde surgen diferentes conceptos y teorías.
      .col-lg-5
        figure(data-aos='flip-right')
          img(src='@/assets/curso/t2-i1.png' alt='imagen decorativa')

    .row.mb-5.justify-content-center
      .col-lg-10
        .cajon.color-acento-contenido.p-4
          p.mb-0  Por lo anterior, se abordará inicialmente el concepto de administración, el proceso administrativo y su aplicabilidad en el deporte.
    
    
    #t_2_1.titulo-segundo.color-secundario
      h2 2.1  Concepto y principios de gestión deportiva y proceso administrativo
    .row.mb-5
      .col-lg-2
        figure(data-aos='slide-right')
          img(src='@/assets/curso/t2-ic1.svg' alt='imagen decorativa')
      .col-lg-10
        p  Abordar los conceptos generales sobre gestión, administración, organización deportiva y proceso administrativo aplicado al deporte permite identificar la interacción de condiciones que van no solo desde lo deportivo, sino también desde lo económico, contable y legal, véalo a continuación:










    Separador
    br
    br
    #t_2_2.titulo-segundo.color-secundario
      h2 2.2  Rol del gestor deportivo







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
