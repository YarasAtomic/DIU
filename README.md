# DIU23
Prácticas Diseño Interfaces de Usuario 2022-23 (Tema: Free Tour) 

Grupo: DIU2.Dunno.  Curso: 2022/23 
Updated: 22/03/2023

Proyecto:
>>> Where2go

Descripción:
>>> Una web clásica de reserva de tours por la ciudad pero que, además, ofrece la posibilidad de crear tus propios itinerarios de ativadades por Granada y compartirlos. Toda esta funcionalidad se integra junto a un detallado sistema de recomendaciones para elegir fácilmente la actividad que mejor se adapta a tu situación.

Logotipo:

<img src="P3/icono.png" style="width:4rem">

Boceto HI-FI:
>>> [Enlace de Figma](https://www.figma.com/proto/6NM0Xleb3hsISxHpgTG1rS/Layout-Hi-Fi-%5BGeneral%5D?node-id=1-2&starting-point-node-id=1%3A2)

Miembros
 * :bust_in_silhouette:  Pablo Quesada Rojo [@pabloqr](https://github.com/pabloqr)
 * :bust_in_silhouette:  Paulina Sedano Motoya [@MissK0u](https://github.com/MissK0u)
 * :bust_in_silhouette:  Guillermo Medialdea Burgos [@YarasAtomic](https://github.com/YarasAtomic)

---

# Proceso de Diseño

A lo largo de este documento vamos a analizar diferentes opciones existentes en la Web, observando sus puntos fuertes y sus debilidades. De esta forma, tomaremos las mejores ideas y añadiremos una propuesta personal para construir una aplicación con un diseño que sea llamativo, útil y accesible a los usuarios. También analizaremos el trabajo realizado por otro grupo de compañeros comparando ambas opciones.

## Paso 1. UX Desk Research & Analisis

En este paso, nos vamos a centrar en una página web con un diseño mejorable, para ello, crearemos *personas* y escenarios que se asemejen lo máximo posible a la realidad y que nos van a ayudar a realizar un análisis detallado de usabilidad de todos los elementos e interacciones que nos permite ejecutar esta web.

El objetivo de esta sección es ponernos en el lugar de los usuarios que acceden al sitio para no cometer los mismos errores. Un elemento importante para esta tarea son los *[empathy map](https://www.interaction-design.org/literature/article/empathy-map-why-and-how-to-use-it)*.

![Método UX](img/Competitive.png) 1.a Competitive Analysis
---

Comenzamos con una comparación de la web proporcionada [Free Tour Granada](https://freetour-granada.com/) con la competencia:
- [Granada Tours](https://granadatours.com.es/): se trata de una opción que, como la proporcionada es mejorable en algunos de sus aspectos.
- [Yoorney - Granada](https://toursgratis.com/granada): se trata de una opción algo mejor que la proporcionada, pero que también tiene algunos aspectos mejorables.
- [Civitatis - Granada](https://www.civitatis.com/es/granada/): se trata de una opción mucho mejor que la proporcionada, con muchas más opciones y una funcionalidad mejor implementada.

![Método UX](img/Persona.png) 1.b Persona
---

Se han creado diferentes perfiles de persona, lo que permite analizar con una mayor profundidad la funcionalidad de la web.

#### Teresa Ferrero

Es una mujer jubilada que le encanta pasar tiempo con su familia y prefiere dedicar su tiempo libre a seguir aprendiendo.
Junto con su marido, realizan viajes por España para conocer la riqueza del país.

<!-- img src="P1/persona_1.png" -->

---

#### Victor García

Se trata de un joven que le gusta disfrutar en la naturaleza, pero que está cansado de su trabajo.
Por esta razón, quiere aprovechar para hacer una escapada con su pareja.

<!-- img src="P1/persona_2.png" -->

---

#### Vincent Matcher

Es un turista inglés de mediana edad, con una vida ya asentada junto a su mujer y sus hijos.
Está totalmente dedicado a su trabajo y, por ello, viaja a España para desconectar y reconciliarse con su familia.

<!-- img src="P1/persona_3.png" -->

![Método UX](img/JourneyMap.png) 1.c User Journey Map
---

En las historias de usuario se han tratado casos prototípicos según los perfiles de las personas creadas.

#### Teresa Ferrero

Su caso es el de una mujer más mayor con pocos conocimientos sobre tecnología pero que se atreve a investigar y probar.
Por este motivo, su objetivo al realizar la reserva es finalizarla lo más rápido posible y con las etapas lo más claras posible.

<!-- img src="P1/journey_map_1.jpeg" -->

---

#### Victor García

Aunque su conocimiento acerca de tecnologías bajo no represente un perfil tan común, sí que lo es el hecho de ser una persona que le gusta aventurarse y conocedora del lenguaje.
Como turista nacional, su objetivo a la hora de realizar la reserva es poder hacerla fácilmente y poder informarse detalladamente acerca del tour.

<!-- img src="P1/journey_map_2.jpeg" -->

---

#### Vincent Matcher

Este sí es un caso muy común, un turista extranjero que busca realizar una actividad cultural en la ciudad.
De este modo, su objetivo es poder realizar el proceso en su idioma nativo y conocer fácilmente a la ubicación del tour.

<!-- img src="P1/journey_map_3.jpeg" -->

![Método UX](img/usabilityReview.png) 1.d Usability Review
---

En nuestro análisis, la web obtiene una puntuación de **58 - Moderate**, que se puede consultar en el [PDF](P1/usability_review_general.pdf) donde se incluyen comentarios a las valoraciones.

La página no presenta una estructura bien definida, lo que hace que encontrar el elemento deseado sea más complejo.
A esto se suma el hecho de que no incluye un buscador o un filtro para los tours y poder agruparlos según su precio, temática…

Por otro lado, el menú tiene pocas opciones y no es muy intuitivo: tiene etiquetas con nombres no muy significativos y no permite ubicarse correctamente dentro de la página.

Pese a ello, el aspecto visual es correcto y el botón de contacto es bastante visible e intuitivo (símbolo de WhatsApp).

En resumen, la página puede presentar algunos puntos positivos, sin embargo, la gran cantidad de errores de diseño y complicación de los procesos que realiza el usuario hacen que la experiencia se vea muy perjudicada.

Se puede consultar más información y los análisis más detallados en el directorio de la [Práctica 1](https://github.com/YarasAtomic/DIU/tree/master/P1).

---

## Paso 2. UX Design  

En este paso, comenzamos nuestro diseño, aportando las ideas principales que se incluirán en nuestra página web, recopilando los mejores aspectos de las webs analizadas, los peores y las ideas nuevas que se incluirán. También propondremos la estructura de la web y realizaremos los primeros bocetos de las principales páginas que se incluirán.

![Método UX](img/feedback-capture-grid.png) 2.a Feedback Capture Grid / EMpathy map / POV
---

Con el trabajo realizado en la parte anterior, hemos descubierto qué elementos de una aplicación pueden considerarse críticos por parte de los usuarios, y qué elementos son los que los desarrolladores dejan de lado. Todo esto es aplicable al tipo de servicio que ofrece nuestra aplicación. En la siguienre matriz se ven más claras todas estas ideas.

<img src="P2/malla_receptora.png">


![Método UX](img/ScopeCanvas.png) 2.b ScopeCanvas
---

Aquí presentamos nuestra aplicación: ***Where2Go*** es una web que pretende acercar Granada a las personas ofreciendo una gran variedad de tours.
Como característica destacable, ***Where2Go*** ofrece a las personas la oportunidad de realizar actividades y compartirlas con el resto de la comunidad de usuarios con el objetivo de realizar ocio alternativo y de forma social. Además la web incluye un sistema de recomendaciones personalizadas fáciles de usar y administrar, especialmente, gracias al sistema de gestión de *viajeros* (usuarios).

![Método UX](img/Sitemap.png) 2.b Tasks analysis 
---

Para calcular la importancia de las tareas dentro de la aplicación, hemos realizado un *Task Matrix* que recoge una gran cantidad de información usando pocos parámetros. En este *Task Matrix* hemos seleccionado las funcionalidades que se pretenden implementar en la aplicación y las hemos asociado a la probabilidad que hay de que un usuario con el perfil indicado (en la columna superior) haga uso de ella. Esto nos permite ordenar estas tareas según la importancia que los usuarios le dan para priorizar las más relevantes.

<img src="P2/matriz_tareas.png">

![Método UX](img/labelling.png) 2.c IA: Sitemap + Labelling 
---

Aquí presentamos la estructura que tendrá la web, explicando la funcionalidad que implementa cada sección.

<img src="P2/labelling.png">


![Método UX](img/Wireframes.png) 2.d Wireframes
---

Finalmente, realizamos los primeros bocetos de las páginas más relevantes, especialmente, de aquellas que tienen más relevancia según el *Task Analysis*.

<img src="P2/wireframe0.png">

En este apartado se muestran tan sólo algunos bocetos, en concreto de la sección *recomendaciones* y *sobre nosotros*, el resto y un informe más detallado de todos los pasos se puede encontrar en el directorio de la [Práctica 2](https://github.com/YarasAtomic/DIU/tree/master/P2).

---

## Paso 3. Mi UX-Case Study (diseño)

En este paso, concluimos el diseño de la página web, de forma que presentamos las características distintivas de nuestro sitio a través del *Moodboard* y, por otro lado, incluimos los diseños finales de las diferentes secciones a partir de los bocetos realizados en el paso anterior.

![Método UX](img/moodboard.png) 3.a Moodboard+Logo
---

>>> El icono se ha diseñado usando *inkscape*. Se ha utilizado una resolución 1024x1024, dado su alto nivel de densidad y su proporción estandar.

Este icono sirve en multiples entornos, como redes sociales, o publicidad. Dispone tan sólo de 2 colores (uno es el blanco), lo cual hace que sea fácil cambiarlos y adaptarlos a mas situaciones.

<img src="P3/icono.png" style="width:4rem">

En el *Moodboard* se define la marca de la web, el nombre, los colores que se van a emplear, indicando cómo se usarán en el texto, el logo, con diferentes variaciones para diferentes formatos en la página. También se incluye el lema que se empleará y las diferentes fuentes y tamaños de fuente que se emplearán a lo largo del sitio.

En este *Moodboard* también se incluyen algunas imágenes de inspiración y comentarios de posibles usuarios del sistema.

<img src="P3/moodboard.png">

![Método UX](img/landing-page.png) 3.b Landing Page
---

La *Landing Page* es la página que verán en primer lugar los usuarios cuando accedan al sitio, de forma que presenta las principales actividades que se pueden realizar en el sistema de la forma más llamativa posible para el usuario.

<img src="P3/landing_page.jpeg">

![Método UX](img/guidelines.png) 3.c Guidelines
---

En este apartado hemos recopilado algunas de las indicaciones y patrones que dictan el diseño de sistemas en la actualidad y que hemos implementado en nuestro diseño:

- [Botones](https://m1.material.io/components/buttons.html#buttons-button-types)
- [Filtros 1](https://ui-patterns.com/patterns/LiveFilter)
- [Filtros 2](https://pencilandpaper.io/articles/ux-pattern-analysis-enterprise-filtering/#sidebar)
- [Registro de cuenta](https://ui-patterns.com/patterns/AccountRegistration)
- [Calendario](https://ui-patterns.com/patterns/CalendarPicker)
- [Carrusel de imágenes](https://ui-patterns.com/patterns/Carousel)

![Método UX](img/mockup.png)  3.d Mockup
---

Finalmente, mostramos los diseños finales para la aplicación que serán accesibles a los usuarios. Se dividen en las diferentes secciones que contiene (y que se especificaron en el *labelling* de la Práctica 2:

#### Itinerarios (Comunidad)

<img src="P3/itinerarios.jpeg">

#### Tour

<img src="P3/lista_tour.jpeg">
<img src="P3/tour.jpeg">

#### Recomendaciones

<img src="P3/recomendaciones.png">

#### Viajero

<img src="P3/viajero.jpeg">

#### Ayuda+Quiénes somos

<img src="P3/ayuda.jpeg">
<img src="P3/quienessomos.png">

![Método UX](img/caseStudy.png) 3.e ¿My UX-Case Study?
---

Video de la simulación:

https://github.com/YarasAtomic/DIU/assets/61023374/ff5f7eea-52cb-43e4-b2aa-be6725107660

Se puede consultar un informe más detallado de todos estos aspectos en el directorio de la [Práctica 3](https://github.com/YarasAtomic/DIU/tree/master/P3).

## Paso 4. Evaluación

En este paso, tomaremos un diseño de otro grupo de compañeros y lo analizaremos a través del *cuestionario SUS*, este cuestionario permite medir de forma universal la percepción de usabilidad de un sistema desde el punto de vista de los usuarios. De esta forma, estos van a ser una parte importante en este análisis y son de los que extraemos las conclusiones para evaluar el diseño. Además, compararemos nuestro propio diseño con el asignado.

![Método UX](img/ABtesting.png) 4.a Caso asignado
---

Se presenta la página web de una empresa que ofrece talleres de cerámica para realizar para todo tipo de personas. Permite ver ejemplos de las actividades y la cerámica. También permite ver cómo trabajan, además de ofrecer reservas para los talleres. Diferencia a los usuarios por nivel de conocimiento en la artesanía. Además, incluye una tienda que ofrece la posibilidad de comprar productos de forma online.

[Enlace al GitHub analizado](https://github.com/AlvaroRodriguezGallardo/DIU)

![Método UX](img/usability-testing.png) 4.b User Testing
---

Se han seleccionado cinco usuarios con diferentes perfiles que nos proporcionen una vista más global de todo el sistema, son los que se muestran a continuación:

<img src="P4/users.jpg">

![Método UX](img/Survey.png). 4.c Cuestionario SUS
---

Para realizar el *cuestionario SUS* se ha pedido a los usuarios que realicen una serie de tareas en el sistema, de esta manera, pueden decidir mejor cuáles son los puntos positivos y negativos de la aplicación y que les permite responder de una forma más objetiva a las cuestiones *SUS*.

Testing del **prototipo A** (Where2Go)

<img src="P4/testingA.jpg">

Testing del **prototipo B** (Artesanía Nazarí)

<img src="P4/testingB.jpg">

![Método UX](img/usability-report.png) 4.d Usability Report
---

Para este apartado se ha preparado un [documento](P4/P4_UsabReport_Artesania_Nazari_doneby_DIU2_DUNNO.pdf) en el que se analiza todo el diseño y en el que se extraen las conclusiones obtenidas del cuestionario y las diferentes pruebas realizadas por los usuarios. Aquí recopilamos lo más relevante de este análisis.

#### Report

En general la página presenta un diseño agradable que hace que los usuarios se sientan cómodos navegando por ella, además, la simplicidad y el hecho de contar con pocas páginas que pueden entrelazar mucho el contenido ayuda a que los usuarios realicen las operaciones deseadas de una forma rápida, fácil e intuitiva.

Sin embargo, esta simplicidad puede ponerse en contra cuando el usuario busca algo más de información sobre ciertos elementos del sitio.

#### Recomendaciones

Las siguientes recomendaciones las hemos extraído de las opiniones de los diferentes usuarios así como de la experiencia propia y el análisis en profundidad de la página web:
 - Cambiar el nombre de ‘TALLER’ de la barra de búsqueda para evitar confusiones, en nuestro caso, inicialmente no entendíamos si se refería al lugar donde se realizan las actividades o a las actividades en sí.
 - El nombre de la página web no aparece en la landing page.
 - Los iconos de las redes sociales se cortan (a veces)
 - El título del icono de la cesta varía el color según la página
 - Los títulos de cada subpágina, tiene un estilo distinto (mayúsculas, negrita, tamaños). Además de que solo la página de tienda tiene un icono.
 - Unificar las fuentes empleadas, especialmente entre la Landing Page y el resto de la web. Resaltar, además, que en la página de inicio se emplea una fuente para las opiniones que no se emplea en ningún otro sitio de la página.
 - Corregir el alineamiento de distintos elementos: secciones de menús desplegables, del texto de la landing page y de secciones dentro de la misma página (galería y página principal). Para mejorar la presentación.
 - El estilo de la página web no es uniforme, la barra superior tiene esquinas redondeadas, mientras que el resto de menús no las tienen, excepto los botones, que además tienen un borde negro.
 - Añadir algunas páginas de información adicional para los productos en las que se pueda consultar en más detalle el proceso de fabricación, el tiempo que tiene y otros datos que pueden ser interesantes para aquellas personas que buscan el lado más instructivo de la página. Y, en especial, se recomienda añadir una página de información para los talleres, para conocer el programa detallado de cada actividad, el número de sesiones, la duración del taller...

Se puede consultar más información en el directorio de la [Práctica 4](https://github.com/YarasAtomic/DIU/tree/master/P4).

## Paso 5. Eye Tracking

En este paso final, realizamos un neuvo test con usuarios que nos da otro parámetro que evalua la calidad de un sitio web. En este caso, obtenemos un mapa de calor de las dos opciones: nos permite detectar cuáles son las zonas en las que los usuarios se centran más, de manera que podemos determinar si ocurre como se esperaba o si hay elementos que destacan y no deberían.

Caso **A**:

https://github.com/YarasAtomic/DIU/assets/126351137/46eb53a3-263e-48bf-a41e-b56c1883bef0

Caso **B**:

<img src="P4/StaticHeatMap_0_( 4s )_AN.jpg">
<img src="P4/StaticHeatMap_1_( 1s )_AN.jpg">
<img src="P4/StaticHeatMap_2_( 1s )_AN.jpg">
<img src="P4/StaticHeatMap_3_( 1s )_AN.jpg">
<img src="P4/StaticHeatMap_4_( 0s )_AN.jpg">
<img src="P4/StaticHeatMap_7_( 1s )_AN.jpg">
<img src="P4/StaticHeatMap_8_( 0s )_AN.jpg">
<img src="P4/StaticHeatMap_9_( 2s )_AN.jpg">
<img src="P4/StaticHeatMap_0_( 4s )p2_AN.jpg">
<img src="P4/StaticHeatMap_1_( 1s )p2_AN.jpg">
<img src="P4/StaticHeatMap_2_( 1s )p2_AN.jpg">
<img src="P4/StaticHeatMap_4_( 1s )p2_AN.jpg">
<img src="P4/StaticHeatMap_5_( 2s )p2_AN.jpg">
<img src="P4/StaticHeatMap_6_( 4s )p2_AN.jpg">
<img src="P4/StaticHeatMap_7_( 0s )p2_AN.jpg">

## Conclusión final / Valoración de las prácticas

