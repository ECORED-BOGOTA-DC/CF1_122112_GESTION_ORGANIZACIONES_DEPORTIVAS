<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Elementos conceptuales del deporte, recreación y actividad física
    .row.mb-5.justify-content-center
      .col-lg-10
        .bloque-texto-g.color-acento-botones.custom-cardBlock.p-3.p-sm-4.p-md-5.slideInUp
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/t1-i1.jpg')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Al definir los términos de deporte, recreación y actividad física, son numerosas las características y nociones que vienen a la mente, las cuales no se deben confundir en sus divergencias a la hora de ser definidas. Lo anterior, unido a la evolución que se le ha dado tanto en tiempo como en las diferentes sociedades, ha hecho que su definición tenga un carácter dinámico y coyuntural. <b>Es por esto que, inicialmente se abordarán los conceptos generales sobre el deporte, recreación, actividad física y ejercicio físico, teniendo en cuenta sus diferencias, características y orientaciones.</b>
    

    #t_1_1.titulo-segundo.color-secundario
      h2 1.1  Concepto y clasificación del deporte, actividad física y recreación
    .row.mb-5
      .col-lg-2
        figure(data-aos='flip-right')
          img(src='@/assets/curso/t1-ic1.svg' alt='imagen decorativa')        
      .col-lg-10
        p.mb-3  El concepto de deporte ha sido estudiado por diferentes autores a lo largo de los años. No obstante, en el medio existe comúnmente una confusión conceptual entre los términos deporte, actividad física, ejercicio físico y la recreación.
        p.mb-3  A continuación, se presentan algunas de las principales diferencias conceptuales existentes en estos cuatro conceptos:
    
    //-- Aqui viene el componente de bloques







    Separador
    br
    br
    #t_1_2.titulo-segundo.color-secundario
      h2 1.2  Características y orientación del deporte
    p.mb-5  La práctica deportiva presenta múltiples características que son clasificadas desde la práctica de carácter profesional, hasta la de carácter lúdico. Entre estas se tiene:
    TabsB.color-acento-contenido.mb-5
      .py-4.py-md-5(titulo="Reglamentación" :icono="require('@/assets/curso/t1-ico1.svg')")
        .row
          .col-md-5
            figure
              img(src='@/assets/curso/t1-i2.png', alt='imagen decorativa')        
          .col-md-7.mb-4.mb-md-0
            h4 Reglamentación
            p Son los principios que dan fundamento a una determinada disciplina, los cuales deben ser conocidos por sus practicantes, con el fin de llevar una ejecución clara y ordenada.

      .py-4.py-md-5(titulo="Competitividad" :icono="require('@/assets/curso/t1-ico1.svg')")
        .row
          .col-md-5
            figure
              img(src='@/assets/curso/t1-i3.png', alt='imagen decorativa')        
          .col-md-7.mb-4.mb-md-0
            h4 Competitividad
            p Son los principios que dan fundamento a una determinada disciplina, los cuales deben ser conocidos por sus practicantes, con el fin de llevar una ejecución clara y ordenada.

      .py-4.py-md-5(titulo="Transmisión de valores" :icono="require('@/assets/curso/t1-ico1.svg')")
        .row
          .col-md-5
            figure
              img(src='@/assets/curso/t1-i4.png', alt='imagen decorativa')        
          .col-md-7.mb-4.mb-md-0
            h4 Transmisión de valores
            p Por medio de la práctica se transmiten e interiorizan valores como el respeto, la honestidad, el esfuerzo y la tolerancia a la frustración, entre otros.
  
      .py-4.py-md-5(titulo="Fomento de los vínculos sociales" :icono="require('@/assets/curso/t1-ico1.svg')")
        .row
          .col-md-5
            figure
              img(src='@/assets/curso/t1-i5.png', alt='imagen decorativa')        
          .col-md-7.mb-4.mb-md-0
            h4 Fomento de los vínculos sociales
            p El principal vínculo es el trabajo en equipo, ya que indiferentemente de la modalidad de la práctica, equipo o individual, se cuenta con todo un grupo de personas que interactúan y velan por el buen cumplimiento del ejercicio, bien sean organizaciones, federaciones, asociaciones, entre otras.    
    
    
    p.mb-5  Así como en las características, las cuales tienen clasificación de carácter profesional y lúdico, en la orientación del deporte también se presenta una clasificación por escenarios, a saber: 

    //-- Aqui viene los nav-holder





    p.mb-5

    TabsA.color-acento-contenido.mb-5
      .tarjeta.color-acento-contenido.p-4(titulo="Organización deportiva")
        .row
          .col-lg-8
            h4 Organización deportiva
            p Slack & Parent (2006) definen la organización deportiva como una entidad social, con objetivos claros y límites bien definidos envuelta en la industria del deporte, según lo cual se debe entender la organización deportiva como una industria en donde hay unos objetivos y metas claras que se deben alcanzar mediante diferentes procesos administrativos.
          .col-lg-4























    //- El componente "Muestras" tiene las aplicaciones de todos los componentes de la base
    //- se encuentra en src/components/Muestras.vue
    //- Una vez el componente "Muestras" no se necesite 
    //- Se debe borrar el "import Muestras from '../components/Muestras'" y en "components" en "<script"
    //- esto evitará que se compile en la carpeta final de distribución
    Muestras
  
</template>

<script>
import Muestras from '../components/Muestras' // borrar una vez el componente "Muestras" no se necesite
export default {
  name: 'Tema1',
  components: {
    Muestras, // borrar una vez el componente "Muestras" no se necesite
  },
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
