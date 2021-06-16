<template lang="pug">
section
  BannerPrincipal.mb-5

  .container.tarjeta.tarjeta__template--azul-claro.px-3.py-4.px-sm-5.pb-sm-5.mb-5
    .titulo__template--a.mb-4
      span.h6 1. Presentación

    p El programa virtual Implementación de escenarios de interoperabilidad con X-ROAD, introducirá a los participantes al diseño e implementación de escenarios de interoperabilidad entre diferentes tipos de sistemas de información y conocimiento, para interactuar hacia objetivos mutuamente beneficiosos, con el propósito de facilitar la entrega de servicios digitales a ciudadanos, empresas y a otras entidades, mediante el intercambio de datos entre sus sistemas TIC, a partir de los elementos y características de la plataforma X-Road, creando una solución de software que involucre un escenario común de interoperabilidad, mediante el uso de la plataforma X-Road.

  .container.tarjeta.tarjeta__template--azul-claro.px-3.py-4.px-sm-5.pb-sm-5.mb-5
        
    .titulo__template--a.mb-4
      span.h6 2. Justificación<br>del programa
  
    .row
      .col-12.col-md-8.col-lg-9
        p.mb-4 El programa Implementación de escenarios de interoperabilidad con X-ROAD involucra a los participantes en un escenario avanzado de interoperabilidad entre diferentes tipos de sistemas de información y conocimiento, para interactuar con objetivos de altos requerimientos en áreas arquitectónicas de escalabilidad y alta disponibilidad de interoperabilidad con X-ROAD, con el propósito de facilitar la entrega de servicios digitales a ciudadanos, empresas y a otras entidades, mediante el intercambio de datos entre sus sistemas TIC, a partir de los elementos y características de esta plataforma, creando una solución de software que involucre un escenario común de interoperabilidad. 

        p.mb-4 El programa está dirigido a servidores públicos (funcionarios y contratistas) y público en general, con el fin de fortalecer las capacidades técnicas y apoyar el cumplimiento de la política de gobierno digital en el habilitador transversal de servicios ciudadanos digitales. 

        p Es así como el SENA, a través de la formación que imparte, permite mantener actualizado el recurso humano con las competencias técnicas y sociales que impactan el sector productivo positivamente, suministrando el conocimiento requerido para el cumplimiento de los planes del Gobierno Nacional por medio del programa Implementación de escenarios de interoperabilidad con X-ROAD.


      .col-4.col-lg-3.d-none.d-md-block
        figure
          img(src='@/assets/curso/05.png', alt='X-Road mintic')    


  .container.tarjeta.tarjeta__template--azul-claro.px-3.py-4.px-sm-5.pb-sm-5.mb-5
    .titulo__template--a.mb-4
      span.h6 3. Competencias<br>a desarrollar

    p  
      span.colorText01
        strong • 
      | Operar herramientas informáticas y digitales de acuerdo con protocolos y manuales técnicos.
  
  .container.tarjeta.tarjeta__template--azul-claro.px-3.py-4.px-sm-5.pb-sm-5.mb-5
    .titulo__template--a.mb-4
      span.h6 4. Perfil<br>de ingreso
    
        
    ul.lista-ul
      li.d-flex  
        i.lista-ul__vineta
        | El público objetivo deberá corresponder a los funcionarios públicos del país (funcionarios y contratistas), los cuales estarán principalmente priorizados por:
      li
        ul
          li.d-flex  
            i.fas.fa-angle-right
            | Servidores públicos (funcionarios y contratistas). 
          li.d-flex  
            i.fas.fa-angle-right
            | CIO, Líderes TI, Servidores de oficinas TI. 
          li.d-flex  
            i.fas.fa-angle-right
            | Personas que han manifestado el desarrollo de proyectos TI bajo el enfoque de interoperabilidad. 
          li.d-flex  
            i.fas.fa-angle-right
            | Priorizar a los servidores del ente territorial sobre el ente nacional de Bogotá. 
          li.d-flex  
            i.fas.fa-angle-right
            | Priorizar a los funcionarios sobre los contratistas.
      li.d-flex  
        i.lista-ul__vineta
        | Haber cursado y aprobado el programa Configurar escenario de interoperabilidad mediante X-ROAD.
      li.d-flex  
        i.lista-ul__vineta
        | Conocimientos en programación y en manejo de repositorio.


  .container.tarjeta.tarjeta__template--azul-claro.px-3.py-4.px-sm-5.pb-sm-5.mb-5
    .titulo__template--a.mb-4
      span.h6 5. Estrategia<br>metodológica

    p.mb-4 Centrada en la construcción de autonomía para garantizar la calidad de los procesos en el marco de la formación por competencias, el aprendizaje por proyectos y el uso de  técnicas didácticas activas que estimulan el pensamiento para la resolución de problemas simulados y reales; soportadas en la utilización de las Tecnologías de la Información y la Comunicación (TIC), integradas en ambientes abiertos y pluritecnológicos, que en todo caso recrean el contexto productivo y vinculan al aprendiz con la realidad cotidiana y el desarrollo de las competencias. 

    p.mb-4 Igualmente, debe estimular de manera permanente la autocrítica y la reflexión del aprendiz sobre el quehacer y los resultados de aprendizaje que logra, a través de la vinculación activa de las cuatro fuentes de información para la construcción de conocimiento:


    .row.g-4.justify-content-center
      .col-5.col-sm-3.col-md-2
        figure.mb-2
          img.w-75.mx-auto(src='@/assets/curso/01.svg', alt='El instructor - tutor')
        p.text-center
          strong El instructor - tutor
      .col-5.col-sm-3.col-md-2
        figure.mb-2
          img.w-75.mx-auto(src='@/assets/curso/02.svg', alt='El instructor - tutor')
        p.text-center
          strong El entorno
      .col-5.col-sm-3.col-md-2
        figure.mb-2
          img.w-75.mx-auto(src='@/assets/curso/03.svg', alt='El instructor - tutor')
        p.text-center
          strong Las TIC

  //- Créditos
  .container.tarjeta.tarjeta__template--azul-claro.px-3.py-4.px-sm-5.mb-5
    .titulo__template--a.mb-4
      span.h6 Créditos

    CreditosComp

  Footer
  

</template>
<script>
import { menuPrincipal } from '../config/global'
import BannerPrincipal from '../components/plantilla/BannerPrincipal'
import CreditosComp from '../components/plantilla/CreditosComp'
import Footer from '../components/plantilla/Footer'
export default {
  name: 'Inicio',
  components: {
    BannerPrincipal,
    CreditosComp,
    Footer,
  },
  data: () => ({
    menuPrincipalData: menuPrincipal,
  }),
  computed: {
    desarrolloContenidosData() {
      const allMenuData = [
        ...this.menuPrincipalData.menu,
        ...this.menuPrincipalData.subMenu,
      ]
      return allMenuData.filter(item => item.desarrolloContenidos)
    },
  },
}
</script>
