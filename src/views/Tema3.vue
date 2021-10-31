<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Legislación y normativa deportiva
    
    .row.mb-5.justify-content-center
      .col-lg-10
        .bloque-texto-g.color-acento-botones.custom-cardBlock.p-3.p-sm-4.p-md-5.slideInUp
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/t3-i1.jpg')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Para el desarrollo de cualquier organización es necesario conocer la legislación y la normativa que lo rige y el sector del deporte no es ajeno a ello. Según lo anterior, se hace necesario abordar temas de conceptualización referentes a la normativa en deporte, el marco legal para el deporte, la actividad física y la recreación a nivel internacional, nacional y local, la estructura nacional del deporte y la conformación de organizaciones deportivas.

    h3.titulo-tercero
      i.fas.fa-check
      | &nbsp;Elementos conceptuales referentes a la normativa deportiva  
    p.mb-5  Reconocer conceptualmente los términos relacionados con la legislación deportiva es indispensable para poder diferenciar y entender su abordaje dentro de las organizaciones deportivas, como son:
    .row.mb-5.justify-content-center
      .col-lg-4
        figure
          img(src='@/assets/curso/t3-i2.jpg')
      .col-lg-6
        AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
          .row(titulo="Acuerdo")
            .col-md-12.mb-4.mb-md-0
              p Decisión tomada en común por dos o más personas, por una junta, asamblea o tribunal. Es la manifestación de una convergencia de voluntades con la finalidad de producir efectos jurídicos.
          .row(titulo="Decreto")
            .col-md-12.mb-4.mb-md-0
              p Es un tipo de acto administrativo emitido por el poder ejecutivo.
          .row(titulo="Ley")
            .col-md-12.mb-4.mb-md-0
              p Precepto dictado por la autoridad competente y cuyo incumplimiento lleva a una sanción; impone deberes y confiere derechos; es de carácter obligatorio. En Colombia las leyes son emitidas a nivel nacional por el Congreso de la República.
          .row(titulo="Marco normativo")
            .col-md-12.mb-4.mb-md-0
              p Es el conjunto de regulaciones jurídicas derivadas de la ley que buscan organizar una sociedad.
          .row(titulo="Norma")
            .col-md-12.mb-4.mb-md-0
              p Es una regla u orden del comportamiento humano.
          .row(titulo="Resolución")
            .col-md-12.mb-4.mb-md-0
              p Es un dictamen que emite un tribunal para ordenar el cumplimiento de una medida o para resolver una petición de alguna de las partes intervinientes en un litigio.
          .row(titulo="Ordenanza")
            .col-md-12.mb-4.mb-md-0
              p Norma jurídica que se incluye dentro de los reglamentos, y que se caracteriza por estar subordinada a la ley. 



    
    #t_3_1.titulo-segundo.color-secundario
      h2 3.1  Marco legal del deporte, actividad física y recreación a nivel internacional, nacional y regional
    .row.mb-5
      .col-lg-7(data-aos='flip-left')
        p.mb-5  Los marcos legales son el conjunto de leyes y reglamentos que indican los límites y las bases sobre las que una persona o una institución puede actuar. El conocimiento del marco legal es de vital importancia para cualquier organización y por supuesto, el sector de la actividad física, el deporte y la recreación no es la excepción; el marco legal permite el direccionamiento adecuado de la organización y la consecución de los recursos según el tipo de organización. Existen diferentes marcos legales y normativos que regulan la creación, garantías, disposiciones, derechos y deberes de las actividades deportivas, físicas y recreativas.
        p.mb-5  Se propone realizar una revisión general de la normativa a nivel internacional, nacional y local, tomando como base las principales ciudades del país. Por ello, a continuación, se expone lo que se trata en estas normativas.
      .col-lg-5
        figure(data-aos='slide-right')
          img(src='@/assets/curso/t3-i3.jpg' alt='imagen decorativa')
    .row.mb-5.justify-content-center
      .col-lg-10
        .cajon.color-acento-contenido.p-4
          p.mb-0  Recuerde, si desea ampliar la información y conocer en detalle cada normativa acceda al final del enlace que se presenta.
    .row.mb-5
      .col-lg-3
        figure(data-aos='slide-right')
          img(src='@/assets/curso/t3-i4.jpg' alt='imagen decorativa')
      .col-lg-9  
        TabsC.color-primario
          .py-3.py-md-4(titulo="Internacional")
            .row
              .col-md-12.mb-4.mb-md-0
                ul.lista-ul
                  li
                    i.fas.fa-check
                    p <b>Carta internacional de la Educación Física, la actividad física y el deporte (UNESCO, 2018).</b> Es el instrumento que garantiza el derecho de acceder al deporte y a la educación física y, contiene diversos principios rectores para la creación y desarrollo de programas deportivos.
                    



    Separador
    br
    br
    #t_3_2.titulo-segundo.color-secundario
      h2 3.2  Estructura nacional del deporte


    Separador
    br
    br
    #t_3_3.titulo-segundo.color-secundario
      h2 3.3  Conformación de organizaciones deportivas

      

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
