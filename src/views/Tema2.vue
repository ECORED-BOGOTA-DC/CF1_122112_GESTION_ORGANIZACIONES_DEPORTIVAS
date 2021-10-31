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
    .row.mb-5.justify-content-center
      .col-lg-8
        figure(data-aos='flip-up')
          img(src='@/assets/curso/t2-i2.png' alt='imagen decorativa')

    TabsA.color-acento-contenido.mb-5
      .tarjeta.color-acento-contenido.p-4(titulo="Organización deportiva")
        .row
          .col-lg-8
            h4 Organización deportiva
            p Slack & Parent (2006) definen la organización deportiva como una entidad social, con objetivos claros y límites bien definidos envuelta en la industria del deporte, según lo cual se debe entender la organización deportiva como una industria en donde hay unos objetivos y metas claras que se deben alcanzar mediante diferentes procesos administrativos.
          .col-lg-4
            figure.slideInLeft
              img(src='@/assets/curso/t2-i3.png' alt='imagen decorativa')

      .tarjeta.color-acento-contenido.p-4(titulo="Proceso administrativo")
        .row
          .col-lg-8
            h4 Proceso administrativo
            p.mb-3  Hace referencia a la administración de la organización en general (planear, organizar, dirigir, ejecutar y controlar), así como también, el uso e implementación de todas aquellas habilidades técnicas, humanas y conceptuales que necesite el administrador para llevar a cabo y desarrollar una gestión efectiva.
            p.mb-3  Asimismo, va adquiriendo un carácter deportivo cuando dichas habilidades de administración y gestión son aplicadas en aquellas entidades e instituciones deportivas que lo requieran para llevar a cabo su objetivos, igualmente para cuando sea necesario llevar acabo el desarrollo de programas, proyectos y eventos deportivos, de recreación, de actividad física, ocio y de aprovechamiento del tiempo libre.
          .col-lg-4
            figure.slideInLeft
              img(src='@/assets/curso/t2-i4.png' alt='imagen decorativa')

      .tarjeta.color-acento-contenido.p-4(titulo="Administración")
        .row
          .col-lg-8
            h4 Administración
            p.mb-3  Comprende los procesos de planeación, organización, dirección, control y evaluación de los recursos de una organización para el logro de un fin u objetivo, buscando emplear los recursos de la organización de una manera eficiente, encaminados al cumplimiento de los objetivos y metas que se planteen.
          .col-lg-4
            figure.slideInLeft
              img(src='@/assets/curso/t2-i5.png' alt='imagen decorativa')

      .tarjeta.color-acento-contenido.p-4(titulo="Gestión")
        .row
          .col-lg-8
            h4 Gestión
            p.mb-3  Se refiere a todo el conjunto de acciones, procedimientos y operaciones que se deberán cumplir en cada objetivo administrativo, para lograr un grado máximo de funcionamiento y una mayor optimización en la entidad deportiva. Con la continua evolución del deporte, demanda de servicios de calidad, incremento de la competitividad empresarial, requerimientos legales y normativos, captación y optimización de recursos, entre muchas otras necesidades que se tienen, se debe tener una óptima gestión del proceso administrativo de dichas empresas.
            p.mb-3  El proceso administrativo cumple con etapas que aunque son similares en todas las empresas no se puede decir que son estándar en su aplicación, ya que cada organización deberá actuar según el contexto, objetivos y estrategias organizacionales.  
          .col-lg-4
            figure.slideInLeft
              img(src='@/assets/curso/t2-i6.png' alt='imagen decorativa')
    p.mb-5  La siguiente tabla permite identificar de forma clara las etapas, definiciones y aspectos claves que se deben tener presentes para establecer un correcto proceso administrativo.
    

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
