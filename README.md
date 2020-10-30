# Bootcamp @Laboratoria

[![All Contributors](https://img.shields.io/badge/all_contributors-55-orange.svg?style=flat-square)](#contributors)
![Node.js CI](https://github.com/Laboratoria/bootcamp/workflows/Node.js%20CI/badge.svg)

## Introducción

El _bootcamp_ de [Laboratoria](https://www.laboratoria.la/) es un **programa de
aprendizaje inmersivo de 6 meses** enfocado en los perfiles de **Front-end
Developer** y **UX Designer**.

Nuestro modelo de aprendizaje se basa en simular un ambiente laboral que te
prepare desarrollando habilidades técnicas y socioemocionales necesarias para
**comenzar** a trabajar.

El **aprendizaje basado en proyectos** es el eje central de la experiencia de
aprendizaje de nuestro _bootcamp_. Trabajar en una serie de _proyectos_, de
complejidad gradualmente creciente, te permitirá ir desarrollando las
habilidades necesarias; de todas las habilidades, consideramos que el
**Autoaprendizaje** es la más importante; no sólo es una habilidad
indispensable para el trabajo que te espera, si no que es también una poderosa
herramienta para ser autosuficiente, segura de tu talento y habilidades.

## Mapa de proyectos

El _mapa de proyectos_ se divide en 4 _etapas_: **Admisión**, **Common Core**,
**Track** (Front-end Development y UX Design) y **Electivos**.

```
Pre    | Common Core          | Track                                                   | Electivos         |
===    | ===========          | =====                                                   | =========         |
       |                      |                                                         |                   |
       |                      |  Frontend                                               |                   |
       |                      |  social-network > md-links     burger-queen             | battleship        |
       |                      |  /                         \  /                       \ |/                  |
       | cipher               | /\                          > -burger-queen-api-client >|-social-network-fw |
       |      \               |/  \                        /  \                       / |\                  |
trivia |        > data-lovers |   md-links > social-network    burger-queen-api         | tic-tac-toe-rn    |
       |      /               |\                                                        |                   |
       | luhn                 | \                                                       | service-design    |
       |                      |  UX                                                     |/                  |
       |                      |  small businesses > redesign-and-data > ux consultancy  |-design-sprint     |
       |                      |                                                         |\                  |
       |                      |                                                         | visual-design     |
       |                      |                                                         |                   |
```

## Evaluación

Durante el transcurso de cada proyecto nuestro equipo de _coaches_ hará un
seguimiento **individual** de tu trabajo y el de tu equipo (si es en grupo).

El tiempo estimado para completar un proyecto puede variar dependiendo de cómo
vayas avanzando y aprendiendo. Asegúrate de conversar con tus _coaches_ para que
te ayuden a planificar y definir el alcance de lo que quieras y necesites
implementar para conseguir los objetivos de aprendizaje del proyecto. Recuerda
que **los objetivos de aprendizaje son más importantes que la completitud de tu
proyecto**.

Al final del proyecto, tendrás una _sesión de feedback_ con tus _coaches_. Antes
de esta sesión tendrás que reflexionar y autoevaluarte respecto a los objetivos
de aprendizaje. En esta sesión de _feedback_ validarás tu autoevaluación con tus
_coaches_. En caso de no haber conseguido algunos objetivos, podrá ocurrir:

* Si se trata de objetivos de aprendizaje que vuelven a aparecer más adelante en
  otros proyectos, pueden quedar simplemente anotados como _pendiente_ y podrás
  continuar con otro proyecto.
* En caso contrario, tus _coaches_ te recomendarán cómo seguir para alcanzar los
  objetivos de aprendizaje que te falten, pudiendo ser a través de continuar con
  el proyecto (más tiempo), hacer un proyecto complementario, etc.

Recuerda que cada una aprende a su ritmo y lo importante es ir obteniendo las
habilidades asociadas a los objetivos de aprendizaje de forma gradual. Tus
_coaches_ y compañeras están ahí para apoyarte.

***

## Etapa 0: Preadmisión

La etapa de _admisión_ empieza _antes_ de ser aceptada a nuestro _bootcamp_. Al
final de cada _proceso de admisión_ invitaremos a candidatas preseleccionadas a
completar presencialmente un _proyecto_ en una de nuestras sedes.

### Proyecto: [Trivia](./projects/00-trivia)

En este proyecto tendrás que construir una aplicación web que le permita a un
usuario responder distintas preguntas escogiendo sus respuestas de una lista de
alternativas.

El objetivo principal de este proyecto es, tener una primera experiencia
desarrollando aplicaciones web (WebApp) que interactúen con el usuario a
través del navegador y la lógica, utilizando HTML, CSS y JavaScript como
herramientas.

* Duración estimada: 3 días.
* Equipos: 2 estudiantes.
* Tópicos: [JavaScript Basics](topics/javascript/01-basics),
  [HTML Intro](topics/html/01-intro), [CSS](topics/css/01-css).

***

## Etapa 1: Common Core

Todas las estudiantes admitidas, comienzan con el _common core_. Durante esta
etapa trabajarás en dos _proyectos_:

1. Primero puedes elegir entre [Cifrado César](projects/01-cipher) y
   [Tarjeta de Crédito Válida](projects/01-card-validation). Ambos proyectos
   comparten los mismos objetivos de aprendizaje.
2. Después, tendrás que trabajar en [Data Lovers](projects/02-data-lovers).

Al final del _common core_ participarás en una o más _hackathones_ trabajando
en proyectos más pequeños propuestos por Laboratoria y/o
empresas/empleadores externos.

### Proyecto: [Cifrado César](projects/01-cipher)

Este _proyecto_ require implementar una aplicación web basada un _boilerplate_
que permita cifrar y descifrar texto usando la técnica del _cifrado césar_.

El principal objetivo de aprendizaje de este proyecto es tener una primera
experiencia construyendo una aplicación web, utilizando los conocimientos
adquiridos sobre **User Experience Design** y **JavaScript**. Esto incluye
diseñar un producto pensando en los usuarios, construir una interfaz, escuchar
eventos básicos del DOM, escribir lógica para llevar a cabo el cifrado y
descifrado, _tests_ unitarios básicos para comprobar (y documentar) dicha
lógica, y manipulación del DOM para mostrar (escribir) los resultados.

* Duración estimada: 2 semanas.
* Equipos: 1 estudiante (individual).
* Tópicos: [Flow control](topics/javascript/02-flow-control),
  [Strings](topics/javascript/06-strings), [Testing](topics/testing),
  [HTML](topics/html), [SCM](topics/scm), [Shell](topics/shell),
  [Intro a UX Design](https://github.com/Laboratoria/curricula-ux/tree/master/00-topics/00-intro-ux).

### Proyecto: [Tarjeta de crédito válida](projects/01-card-validation)

Este _proyecto_ requiere implementar una aplicación web basada un _boilerplate_
que permita a un usuario validar el número de una tarjeta de crédito y además
ocultar todos los dígitos de la tarjeta menos los últimos cuatro.

El principal objetivo de aprendizaje de este proyecto es tener una primera
experiencia construyendo una aplicación web, utilizando los conocimientos
adquiridos sobre **User Experience Design** y **JavaScript**. Esto incluye
diseñar un producto pensando en los usuarios, construir una interfaz, escuchar
eventos básicos del DOM, escribir lógica para llevar a cabo el cifrado y
descifrado, _tests_ unitarios básicos para comprobar (y documentar) dicha
lógica, y manipulación del DOM para mostrar (escribir) los resultados.

* Duración estimada: 2 semanas.
* Equipos: 1 estudiante (individual).
* Tópicos: [Flow control](topics/javascript/02-flow-control),
  [Strings](topics/javascript/06-strings), [Testing](topics/testing),
  [HTML](topics/html), [SCM](topics/scm), [Shell](topics/shell),
  [Intro a UX Design](https://github.com/Laboratoria/curricula-ux/tree/master/00-topics/00-intro-ux).

### Proyecto: [Data Lovers](projects/02-data-lovers)

En este proyecto tendrás tu primer acercamiento a transformar _data_ en
información. El objetivo principal de este proyecto es aprender a diseñar y
construir una _interfaz web_ donde podamos visualizar y manipular _data_.

Esperamos que puedan pensar en el usuario, entender cuál es la mejor manera de
visualizar la data en la web según sus necesidades.

Este proyecto se debe "resolver" en duplas, por lo que un objetivo importante
es ganar experiencia en trabajo colaborativo con toda la complejidad que
eso implica.

* Duración estimada: 4 semanas.
* Equipos: 2 estudiantes.
* Tópicos: [Arrays](topics/javascript/04-arrays),
  [Objects](topics/javascript/05-objects), [DOM](topics/browser/02-dom),
  [XHR/fetch](topics/browser/04-xhr), [Visual Design](https://github.com/Laboratoria/curricula-ux/tree/master/00-topics/02-diseno-visual).

***

## Etapa 2: Tracks

Después del _common core_ cada grupo se separa en _tracks especializados_ y
paralelos: _Front-end Development y UX Design_.

### Track Front-end Development

Tópicos comunes (uno o más proyectos): [Paradigmas](topics/paradigms),
[JavaScript Funcional](topics/functional).

#### Proyecto: [Red Social](projects/03-social-network)

En este _proyecto_ partimos del supuesto que una emprendedora ha pedido hacer
un prototipo para una _red social_ sobre algunos temas de entre los cuales
deberás elegir.

El objetivo de aprendizaje principal de este proyecto es construir un sitio web
[_responsive_](https://github.com/Laboratoria/bootcamp/tree/master/topics/css/02-responsive)
con más de una vista (página), y en el que podamos leer y escribir datos
entendiendo las necesidades de los usuarios.

* Duración estimada: 3 semanas.
* Equipos: 3 estudiantes.
* Tópicos: **Mobile first**, [Responsive](topics/css/02-responsive), URL, HTTP,
  [Async](topics/javascript/08-async), Múltiples vistas, Routing, Escritura de
  datos, `localStorage`, [Firebase](https://firebase.google.com/).

#### Proyecto: [Markdown Links](projects/04-md-links)

Dentro de una comunidad de código abierto, proponen crear una herramienta
usando [Node.js](https://nodejs.org/), que lea y analice archivos en formato
`Markdown`, para verificar los links que contengan y reportar
algunas estadísticas al respecto.

El objetivo práctico de este proyecto es aprender a crear una **librería**
(o biblioteca - _library_) en JavaScript.

Diseñar una librería es una experiencia fundamental para cualquier
desarrolladora porque que le obliga a pensar en la interfaz (API) de sus
_módulos_ y cómo será usada por otros _developers_. Se necesita tener especial
consideración en peculiaridades del lenguaje, convenciones y "buenas prácticas".

* Duración estimada: 3 semanas.
* Equipos: 1 estudiante.
* Tópicos: Node.js, NPM, File System, Semver, Parsing, Markdown, CLI, HTTP,
  Módulos, [Errores](topics/javascript/09-errors).

#### Proyecto: [Burger Queen Serverless](projects/04-burger-queen)

Este _proyecto_ requiere implementar un sistema para que lxs meserxs de un
restautante (_Burger Queen_) puedan tomar nota de los pedidos usando una
_tablet_.

El objetivo de aprendizaje principal de este proyecto es construir una
_interfaz web_ usando un _framework_ (React, Vue o Angular).

Como objetivo secundario, la implementación debe seguir las recomendaciones
para PWAs (_Progressive Web Apps_), lo cual incluye conceptos como **offline**.

* Duración estimada: 3 semanas.
* Equipos: 1-2 estudiantes.
* Tópicos: Frameworks, React, Vue, Angular, PWA, Offline First,
  Service Workers, Serverless.

#### Proyecto: [Burger Queen HTTP/JSON API](projects/04-burger-queen-api)

El objetivo de aprendizaje principal es adquirir experiencia con **Node.js**
como herramienta para desarrollar _aplicaciones de servidor_, junto con una
serie de herramientas comunes usadas en este tipo de contexto (Express como
_framework_, MongoDB como base datos, etc.).

En este proyecto tendrás que construir un servidor web que debe _servir_ `JSON`
sobre `HTTP`.

En este proyecto partimos de un _boilerplate_ que ya contiene una serie de
_endpoints_ (puntos de conexión o URLs) y nos piden completar la aplicación.
Esto implica que tendremos que partir por leer la implementación existente, y
familiarizarnos con el _stack_ elegido: [Node.js](https://nodejs.org/),
[Express](https://expressjs.com/), [MongoDB](https://www.mongodb.com/),
[mongoose](https://mongoosejs.com/), ...

* Duración estimada: 2 semanas.
* Equipos: 1 estudiante
* Tópicos: Node.js, Express, _rutas_ (_routes_), URLs, HTTP (verbs, request,
  response, headers, body, status codes...), JSON, MongoDB,
  _variables de entorno_, JWT (_JSON Web Tokens_)...

#### Proyecto: [Burger Queen API Client](projects/04-burger-queen-api-client)

Este _proyecto_ requiere implementar un sistema para que lxs meserxs de un
restautante (_Burger Queen_) puedan tomar nota de los pedidos usando una
_tablet_.

El objetivo principal de aprendizaje de este proyecto es construir una
_interfaz web_ usando un _framework_ (React, Vue o Angular).

Como objetivo secundario, la implementación debe seguir las recomendaciones
para PWAs (_Progressive Web Apps_), lo cual incluye conceptos como **offline**.

* Duración estimada: 3 semanas.
* Equipos: 1-2 estudiantes.
* Tópicos: Frameworks, React, Vue, Angular, PWA, Offline First,
  Service Workers, HTTP, JSON, `fetch`.

### Track UX Design

#### Proyecto: [Emprendimientos](projects/03-small-businesses)

Para este proyecto inicial del _track_, trabajarás con pequeños emprendimientos
para ofrecer una nueva y/o mejor experiencia _online_ para sus usuarios. Para
eso, tienes que entender los objetivos de negocio del emprendimiento y las
necesidades de sus usuarios/clientes. Durante este proyecto harás trabajo de
campo: entrevistas, observación y _testing_ y diseñarás soluciones utilizando
herramientas de diseño como Figma y Marvel.

* Duración estimada: 3 semanas
* Equipos: 2 o 3 estudiantes
* Tópicos: UX research (entrevistas, benchmark), arquitectura de la información
  (flujo de contenido, mapa de sitio), diseño visual y de interacción
  (wireframes y prototipado), y user testing

#### Proyecto: [Rediseño y Análisis de Data](projects/04-redesign-and-data)

Este es un proyecto de rediseño de un producto existente. Basándose en la data
de los resultados que está teniendo una aplicación de servicios financieros,
deberás mejorar la experiencia de la misma.

En algunas casos este proyecto puede ser reemplazado por un uno con una
empresa, pero tendrá siempre los mismos objetivos de aprendizaje.

* Duración estimada: 3 semanas
* Equipos: 2 o 3 estudiantes
* Tópicos: Data analysis, UX Research, prototipado, ideación, visual design

#### Proyecto: [Consultoría UX](projects/05-ux-consultancy)

Trabajarás en distintos casos reales propuestos por empresas de diversos rubros
y tamaños. En el pasado se ha trabajado con empresas como Kmimos, Guvery,
Globant, Sinenvolturas, Magical Startups, Laboratoria, entre otras.

* Duración estimada: 3 semanas
* Equipos: Depende de proyectos
* Tópicos: UX Research, prototipado, ideación, visual design

***

## Etapa 3: Electivos

La última parte del _bootcamp_, y dependiendo de cómo hayas conseguido los
objetivos de aprendizaje de los anteriores proyectos, podrás aprovechar para
elegir trabajar en un proyecto _final_ que puede estar basado en los
tópicos/tecnologías vistas hasta el momento, o puede cubrir algunos de los
tópicos adicionales sugeridos.

### Track Front-end Development

#### Proyecto: [Tic Tac Toe Con React Native](projects/05-tic-tac-toe-rn)

El objetivo de aprendizaje principal es tener una primera experiencia en
desarrollo de una aplicación usando React Native y Expo, y publicarla en tu
cuenta de Expo para que se pueda instalar en cualquier dispositivo Android o iOS.

Tendrás que familiarizarte con conceptos como `View`, `Text` o
`TouchableOpacity` y con el flujo de desarrollo propio de apps nativas.

* Duración estimada: 2 semanas.
* Equipos: 1 estudiante
* Tópicos: React Native, Expo, componentes nativos, touch events, ...

#### Proyecto: [Battleship](projects/05-battleship)

Battleship es un juego clásico, con múltiples versiones en juegos de mesa y en
línea (si no lo conoces, puedes verlo en este link :
[battle-ship](https://es.wikipedia.org/wiki/Batalla_naval_(juego))).

En este proyecto deberás crear una nueva versión, agregándole algún giro para
actualizarlo y hacerlo más atractivo para las nuevas generaciones. No estás
atada a hacer este juego sobre barcos, puedes hacerlo con el tema que más
te guste, siempre y cuando el modo de juego sea parecido.

* Duración estimada: 2 semanas.
* Equipos: 3 estudiantes
* Tópicos: _react_, _angular_, _redux_, _firebase_, _mongodb stitch_.

#### Proyecto: [Red Social (con Frameworks)](projects/05-social-network-fw)

En este proyecto tendrás la oportunidad de _re-escribir_ tu anterior proyecto de
la _Red Social_, pero esta vez usando un _framework_ o una _librería_.

Creemos que una muy buena manera de profundizar en estas herramientas puede ser
eliminando de la ecuación el hecho de que tengas que entender un proyecto desde
cero, su alcance, sus particularidades, el flujo, las validaciones, etc.
Concéntrate en aprender y utilizar estas nuevas tecnologías.

* Duración estimada: 2 semanas.
* Equipos: 1-2 estudiantes
* Tópicos: _react_, _angular_, _vue_, _firebase_.

### Track UX Design

#### Proyecto: [Visual Design](projects/06-visual-design)

En este proyecto buscamos mejorar las habilidades de diseño visual de interfaces.
Para ello, las trabajarás en cómo mejorar y unificar la experiencia de una
plataforma de venta de entradas a espectáculos (tradicional) para ayudarlos a
competir con nuevos actores en la industria como Stubhub, Eventbrite, Joinnus,
entre otros.

Tendrán que crear soluciones consistentes para _mobile_, _desktop_ y
_smartwatches_. En algunas casos este proyecto puede ser reemplazado por uno
con una empresa, pero con los mismos objetivos de aprendizaje.

* Duración estimada: 3 semanas
* Equipos: Depende de proyectos
* Tópicos: Design Systems, Grid systems, atomic design, componentes,
  consistencia,jerarquía, responsive design.

#### Proyecto: [Service Design](projects/06-service-design)

Con la ayuda de consultoras especializadas como Amable o Touchpoint,
te sumergirás  en el mundo del _service design_ (diseño de servicios)
entendiendo problemas de negocio desde una visión más holística y utilizando
nuevas herramientas como el _Service BluePrint_.

* Duración estimada: 3 semanas
* Equipos: Depende de proyectos
* Tópicos: Service design, disruptive design, insights, service prototyping,
  service blue print

***

## Índice de tópicos

* [JavaScript](topics/javascript)
* [HTML](topics/html)
* [CSS](topics/css)
* [Browser JavaScript](topics/browser)
* [SCM: Git + GitHub](topics/scm)
* [UNIX Shell](topics/shell)
* [Paradigmas de programación](topics/paradigms)
* [JavaScript Funcional](topics/functional)
* [Intro a UX Design](topics/intro-ux)
* [Content Management](topics/content-management)
* [Interaction Design](topics/interaction-design)
* [UX Research](topcis/ux-research)
* [Prototyping](topcis/prototyping)

***

## Contribuciones

Toda contribución es **gratamente bienvenida**.

Pero **POR FAVOR** no olvides leer detalladamente la
[guía para contribuidores](CONTRIBUTING.md) antes de enviar un PR.

Muchas gracias a toda esta gente maravillosa ([leyenda de emojis](https://github.com/kentcdodds/all-contributors#emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
<table><tr><td align="center"><a href="https://www.youtube.com/user/lupomontero"><img src="https://avatars3.githubusercontent.com/u/110297?v=4" width="100px;" alt="Lupo Montero"/><br /><sub><b>Lupo Montero</b></sub></a><br /><a href="#question-lupomontero" title="Answering Questions">💬</a> <a href="https://github.com/Laboratoria/bootcamp/issues?q=author%3Alupomontero" title="Bug reports">🐛</a> <a href="https://github.com/Laboratoria/bootcamp/commits?author=lupomontero" title="Code">💻</a> <a href="https://github.com/Laboratoria/bootcamp/commits?author=lupomontero" title="Documentation">📖</a> <a href="#example-lupomontero" title="Examples">💡</a> <a href="#ideas-lupomontero" title="Ideas, Planning, & Feedback">🤔</a> <a href="#infra-lupomontero" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a> <a href="#plugin-lupomontero" title="Plugin/utility libraries">🔌</a> <a href="#review-lupomontero" title="Reviewed Pull Requests">👀</a> <a href="https://github.com/Laboratoria/bootcamp/commits?author=lupomontero" title="Tests">⚠️</a> <a href="#tool-lupomontero" title="Tools">🔧</a> <a href="#video-lupomontero" title="Videos">📹</a></td><td align="center"><a href="https://github.com/chamodev"><img src="https://avatars3.githubusercontent.com/u/25286921?v=4" width="100px;" alt="chamodev"/><br /><sub><b>chamodev</b></sub></a><br /><a href="#ideas-chamodev" title="Ideas, Planning, & Feedback">🤔</a> <a href="#translation-chamodev" title="Translation">🌍</a></td><td align="center"><a href="https://www.facebook.com/medinadiazivan"><img src="https://avatars3.githubusercontent.com/u/9284690?v=4" width="100px;" alt="Ivan Medina"/><br /><sub><b>Ivan Medina</b></sub></a><br /><a href="#question-ivandevp" title="Answering Questions">💬</a> <a href="https://github.com/Laboratoria/bootcamp/issues?q=author%3Aivandevp" title="Bug reports">🐛</a> <a href="https://github.com/Laboratoria/bootcamp/commits?author=ivandevp" title="Code">💻</a> <a href="#example-ivandevp" title="Examples">💡</a> <a href="#review-ivandevp" title="Reviewed Pull Requests">👀</a></td><td align="center"><a href="https://github.com/merunga"><img src="https://avatars2.githubusercontent.com/u/211721?v=4" width="100px;" alt="Mariano Crowe"/><br /><sub><b>Mariano Crowe</b></sub></a><br /><a href="#question-merunga" title="Answering Questions">💬</a> <a href="https://github.com/Laboratoria/bootcamp/issues?q=author%3Amerunga" title="Bug reports">🐛</a> <a href="https://github.com/Laboratoria/bootcamp/commits?author=merunga" title="Code">💻</a> <a href="https://github.com/Laboratoria/bootcamp/commits?author=merunga" title="Documentation">📖</a> <a href="#example-merunga" title="Examples">💡</a> <a href="#ideas-merunga" title="Ideas, Planning, & Feedback">🤔</a> <a href="#review-merunga" title="Reviewed Pull Requests">👀</a></td><td align="center"><a href="https://github.com/diegovelezg"><img src="https://avatars0.githubusercontent.com/u/28717078?v=4" width="100px;" alt="Diego"/><br /><sub><b>Diego</b></sub></a><br /><a href="https://github.com/Laboratoria/bootcamp/issues?q=author%3Adiegovelezg" title="Bug reports">🐛</a> <a href="#ideas-diegovelezg" title="Ideas, Planning, & Feedback">🤔</a></td><td align="center"><a href="https://anasalazar.github.io/"><img src="https://avatars1.githubusercontent.com/u/25916511?v=4" width="100px;" alt="Ana Steph"/><br /><sub><b>Ana Steph</b></sub></a><br /><a href="#question-AnaSalazar" title="Answering Questions">💬</a> <a href="https://github.com/Laboratoria/bootcamp/issues?q=author%3AAnaSalazar" title="Bug reports">🐛</a> <a href="https://github.com/Laboratoria/bootcamp/commits?author=AnaSalazar" title="Code">💻</a></td><td align="center"><a href="https://github.com/lalogf"><img src="https://avatars1.githubusercontent.com/u/8517182?v=4" width="100px;" alt="Lalo Gonzalez"/><br /><sub><b>Lalo Gonzalez</b></sub></a><br /><a href="#question-lalogf" title="Answering Questions">💬</a> <a href="#design-lalogf" title="Design">🎨</a> <a href="#ideas-lalogf" title="Ideas, Planning, & Feedback">🤔</a></td></tr><tr><td align="center"><a href="http://milmazz.uno"><img src="https://avatars3.githubusercontent.com/u/34700?v=4" width="100px;" alt="Milton Mazzarri"/><br /><sub><b>Milton Mazzarri</b></sub></a><br /><a href="https://github.com/Laboratoria/bootcamp/commits?author=milmazz" title="Code">💻</a> <a href="#example-milmazz" title="Examples">💡</a></td><td align="center"><a href="https://github.com/RuthSalvador"><img src="https://avatars3.githubusercontent.com/u/25906896?v=4" width="100px;" alt="Ruth Abigail Salvador Zorrilla"/><br /><sub><b>Ruth Abigail Salvador Zorrilla</b></sub></a><br /><a href="https://github.com/Laboratoria/bootcamp/issues?q=author%3ARuthSalvador" title="Bug reports">🐛</a> <a href="#ideas-RuthSalvador" title="Ideas, Planning, & Feedback">🤔</a></td><td align="center"><a href="https://maiarojas.github.io/Portafolio_v1/"><img src="https://avatars3.githubusercontent.com/u/25912510?v=4" width="100px;" alt="Maricarmen Rojas Tinco"/><br /><sub><b>Maricarmen Rojas Tinco</b></sub></a><br /><a href="https://github.com/Laboratoria/bootcamp/issues?q=author%3AMaiaRojas" title="Bug reports">🐛</a> <a href="https://github.com/Laboratoria/bootcamp/commits?author=MaiaRojas" title="Code">💻</a> <a href="https://github.com/Laboratoria/bootcamp/commits?author=MaiaRojas" title="Tests">⚠️</a></td><td align="center"><a href="https://github.com/MariPlaza"><img src="https://avatars0.githubusercontent.com/u/14231402?v=4" width="100px;" alt="María Inés Plaza Schwarck"/><br /><sub><b>María Inés Plaza Schwarck</b></sub></a><br /><a href="https://github.com/Laboratoria/bootcamp/commits?author=MariPlaza" title="Code">💻</a> <a href="#example-MariPlaza" title="Examples">💡</a></td><td align="center"><a href="https://github.com/brecabal"><img src="https://avatars1.githubusercontent.com/u/20929277?v=4" width="100px;" alt="Belén Recabal"/><br /><sub><b>Belén Recabal</b></sub></a><br /><a href="https://github.com/Laboratoria/bootcamp/issues?q=author%3Abrecabal" title="Bug reports">🐛</a> <a href="#ideas-brecabal" title="Ideas, Planning, & Feedback">🤔</a></td><td align="center"><a href="https://github.com/developerVilchez"><img src="https://avatars2.githubusercontent.com/u/28201139?v=4" width="100px;" alt="Lourdes Vílchez"/><br /><sub><b>Lourdes Vílchez</b></sub></a><br /><a href="https://github.com/Laboratoria/bootcamp/issues?q=author%3AdeveloperVilchez" title="Bug reports">🐛</a> <a href="#ideas-developerVilchez" title="Ideas, Planning, & Feedback">🤔</a></td><td align="center"><a href="https://github.com/FabianBravoA"><img src="https://avatars0.githubusercontent.com/u/7809496?v=4" width="100px;" alt="Fabian Alexis Bravo Abarca"/><br /><sub><b>Fabian Alexis Bravo Abarca</b></sub></a><br /><a href="https://github.com/Laboratoria/bootcamp/issues?q=author%3AFabianBravoA" title="Bug reports">🐛</a> <a href="https://github.com/Laboratoria/bootcamp/commits?author=FabianBravoA" title="Code">💻</a> <a href="#example-FabianBravoA" title="Examples">💡</a> <a href="#ideas-FabianBravoA" title="Ideas, Planning, & Feedback">🤔</a> <a href="#review-FabianBravoA" title="Reviewed Pull Requests">👀</a></td></tr><tr><td align="center"><a href="https://github.com/AmaliaRiveraC"><img src="https://avatars3.githubusercontent.com/u/25911727?v=4" width="100px;" alt="Amalia Rivera Castillejos"/><br /><sub><b>Amalia Rivera Castillejos</b></sub></a><br /><a href="https://github.com/Laboratoria/bootcamp/issues?q=author%3AAmaliaRiveraC" title="Bug reports">🐛</a> <a href="#ideas-AmaliaRiveraC" title="Ideas, Planning, & Feedback">🤔</a></td><td align="center"><a href="https://github.com/shirley-startary"><img src="https://avatars0.githubusercontent.com/u/25912292?v=4" width="100px;" alt="Shirley Silvana Suarez Startary"/><br /><sub><b>Shirley Silvana Suarez Startary</b></sub></a><br /><a href="#question-shirley-startary" title="Answering Questions">💬</a> <a href="https://github.com/Laboratoria/bootcamp/issues?q=author%3Ashirley-startary" title="Bug reports">🐛</a> <a href="https://github.com/Laboratoria/bootcamp/commits?author=shirley-startary" title="Code">💻</a> <a href="#example-shirley-startary" title="Examples">💡</a> <a href="#ideas-shirley-startary" title="Ideas, Planning, & Feedback">🤔</a></td><td align="center"><a href="https://github.com/nerdale"><img src="https://avatars3.githubusercontent.com/u/20868992?v=4" width="100px;" alt="Alexandra Neira"/><br /><sub><b>Alexandra Neira</b></sub></a><br /><a href="https://github.com/Laboratoria/bootcamp/issues?q=author%3Anerdale" title="Bug reports">🐛</a> <a href="#ideas-nerdale" title="Ideas, Planning, & Feedback">🤔</a></td><td align="center"><a href="https://michellesegv.github.io/"><img src="https://avatars0.githubusercontent.com/u/10764912?v=4" width="100px;" alt="Michelle Seguil"/><br /><sub><b>Michelle Seguil</b></sub></a><br /><a href="https://github.com/Laboratoria/bootcamp/issues?q=author%3Amichellesegv" title="Bug reports">🐛</a> <a href="https://github.com/Laboratoria/bootcamp/commits?author=michellesegv" title="Code">💻</a> <a href="#example-michellesegv" title="Examples">💡</a> <a href="#ideas-michellesegv" title="Ideas, Planning, & Feedback">🤔</a></td><td align="center"><a href="https://github.com/CaroLaboratoria"><img src="https://avatars1.githubusercontent.com/u/28611099?v=4" width="100px;" alt="Carolina Covarrubias"/><br /><sub><b>Carolina Covarrubias</b></sub></a><br /><a href="#question-CaroLaboratoria" title="Answering Questions">💬</a> <a href="https://github.com/Laboratoria/bootcamp/commits?author=CaroLaboratoria" title="Documentation">📖</a> <a href="#ideas-CaroLaboratoria" title="Ideas, Planning, & Feedback">🤔</a></td><td align="center"><a href="https://github.com/joalbertg"><img src="https://avatars1.githubusercontent.com/u/13588707?v=4" width="100px;" alt="Joalbert Andrés González"/><br /><sub><b>Joalbert Andrés González</b></sub></a><br /><a href="#ideas-joalbertg" title="Ideas, Planning, & Feedback">🤔</a></td><td align="center"><a href="https://github.com/lizzie136"><img src="https://avatars2.githubusercontent.com/u/3421560?v=4" width="100px;" alt="Elizabeth Portilla"/><br /><sub><b>Elizabeth Portilla</b></sub></a><br /><a href="#question-lizzie136" title="Answering Questions">💬</a> <a href="https://github.com/Laboratoria/bootcamp/issues?q=author%3Alizzie136" title="Bug reports">🐛</a> <a href="#ideas-lizzie136" title="Ideas, Planning, & Feedback">🤔</a></td></tr><tr><td align="center"><a href="https://www.linkedin.com/in/karlanavamuci%C3%B1o/"><img src="https://avatars2.githubusercontent.com/u/25912346?v=4" width="100px;" alt="Karla Nava "/><br /><sub><b>Karla Nava </b></sub></a><br /><a href="#ideas-karlanavam" title="Ideas, Planning, & Feedback">🤔</a></td><td align="center"><a href="https://medium.com/@BosqueInvierno"><img src="https://avatars0.githubusercontent.com/u/17767965?v=4" width="100px;" alt="Allison Guzmán"/><br /><sub><b>Allison Guzmán</b></sub></a><br /><a href="https://github.com/Laboratoria/bootcamp/issues?q=author%3Abosqueinvierno" title="Bug reports">🐛</a> <a href="#ideas-bosqueinvierno" title="Ideas, Planning, & Feedback">🤔</a></td><td align="center"><a href="https://github.com/alejandrarv"><img src="https://avatars3.githubusercontent.com/u/30906042?v=4" width="100px;" alt="Alejandra Ramirez"/><br /><sub><b>Alejandra Ramirez</b></sub></a><br /><a href="#ideas-alejandrarv" title="Ideas, Planning, & Feedback">🤔</a></td><td align="center"><a href="https://www.linkedin.com/in/aocsa/"><img src="https://avatars3.githubusercontent.com/u/3615859?v=4" width="100px;" alt="Alexander Ocsa"/><br /><sub><b>Alexander Ocsa</b></sub></a><br /><a href="https://github.com/Laboratoria/bootcamp/issues?q=author%3Aaocsa" title="Bug reports">🐛</a></td><td align="center"><a href="https://github.com/rocioalberdi"><img src="https://avatars3.githubusercontent.com/u/29586691?v=4" width="100px;" alt="Rocío Alberdi"/><br /><sub><b>Rocío Alberdi</b></sub></a><br /><a href="#ideas-rocioalberdi" title="Ideas, Planning, & Feedback">🤔</a></td><td align="center"><a href="https://memecast.github.io/"><img src="https://avatars0.githubusercontent.com/u/25912393?v=4" width="100px;" alt="Ameli C. Gavante"/><br /><sub><b>Ameli C. Gavante</b></sub></a><br /><a href="https://github.com/Laboratoria/bootcamp/issues?q=author%3Amemecast" title="Bug reports">🐛</a> <a href="#ideas-memecast" title="Ideas, Planning, & Feedback">🤔</a></td><td align="center"><a href="https://github.com/IntiDev"><img src="https://avatars0.githubusercontent.com/u/25912534?v=4" width="100px;" alt="IntiDev"/><br /><sub><b>IntiDev</b></sub></a><br /><a href="https://github.com/Laboratoria/bootcamp/issues?q=author%3AIntiDev" title="Bug reports">🐛</a> <a href="#ideas-IntiDev" title="Ideas, Planning, & Feedback">🤔</a></td></tr><tr><td align="center"><a href="http://emmanuelorozco.com"><img src="https://avatars3.githubusercontent.com/u/5270810?v=4" width="100px;" alt="Emmanuel Orozco"/><br /><sub><b>Emmanuel Orozco</b></sub></a><br /><a href="https://github.com/Laboratoria/bootcamp/issues?q=author%3Aindie-rok" title="Bug reports">🐛</a> <a href="https://github.com/Laboratoria/bootcamp/commits?author=indie-rok" title="Code">💻</a> <a href="#ideas-indie-rok" title="Ideas, Planning, & Feedback">🤔</a></td><td align="center"><a href="http://www.nicolethenerd.com"><img src="https://avatars0.githubusercontent.com/u/1126193?v=4" width="100px;" alt="Nicole Stein"/><br /><sub><b>Nicole Stein</b></sub></a><br /><a href="https://github.com/Laboratoria/bootcamp/commits?author=nicolethenerd" title="Code">💻</a> <a href="#example-nicolethenerd" title="Examples">💡</a> <a href="#ideas-nicolethenerd" title="Ideas, Planning, & Feedback">🤔</a></td><td align="center"><a href="https://github.com/giancorzo"><img src="https://avatars3.githubusercontent.com/u/501129?v=4" width="100px;" alt="Giancarlo Corzo"/><br /><sub><b>Giancarlo Corzo</b></sub></a><br /><a href="https://github.com/Laboratoria/bootcamp/issues?q=author%3Agiancorzo" title="Bug reports">🐛</a> <a href="#ideas-giancorzo" title="Ideas, Planning, & Feedback">🤔</a></td><td align="center"><a href="https://github.com/arcuellar88"><img src="https://avatars3.githubusercontent.com/u/9292999?v=4" width="100px;" alt="Alejandro Rodriguez Cuellar"/><br /><sub><b>Alejandro Rodriguez Cuellar</b></sub></a><br /><a href="https://github.com/Laboratoria/bootcamp/commits?author=arcuellar88" title="Code">💻</a> <a href="#ideas-arcuellar88" title="Ideas, Planning, & Feedback">🤔</a></td><td align="center"><a href="https://github.com/gaposx"><img src="https://avatars2.githubusercontent.com/u/539819?v=4" width="100px;" alt="Gonzalo Parra"/><br /><sub><b>Gonzalo Parra</b></sub></a><br /><a href="#question-gaposx" title="Answering Questions">💬</a> <a href="https://github.com/Laboratoria/bootcamp/issues?q=author%3Agaposx" title="Bug reports">🐛</a> <a href="#example-gaposx" title="Examples">💡</a> <a href="#ideas-gaposx" title="Ideas, Planning, & Feedback">🤔</a> <a href="#review-gaposx" title="Reviewed Pull Requests">👀</a></td><td align="center"><a href="https://cristiancardenas.cl"><img src="https://avatars3.githubusercontent.com/u/25645113?v=4" width="100px;" alt="Cristian K. Cárdenas"/><br /><sub><b>Cristian K. Cárdenas</b></sub></a><br /><a href="#example-ccardensa" title="Examples">💡</a></td><td align="center"><a href="https://github.com/Jonhks"><img src="https://avatars1.githubusercontent.com/u/25328635?v=4" width="100px;" alt="Jonhks"/><br /><sub><b>Jonhks</b></sub></a><br /><a href="https://github.com/Laboratoria/bootcamp/issues?q=author%3AJonhks" title="Bug reports">🐛</a> <a href="https://github.com/Laboratoria/bootcamp/commits?author=Jonhks" title="Code">💻</a> <a href="#ideas-Jonhks" title="Ideas, Planning, & Feedback">🤔</a></td></tr><tr><td align="center"><a href="https://github.com/Gabx04"><img src="https://avatars1.githubusercontent.com/u/16655830?v=4" width="100px;" alt="Gabriela Segura"/><br /><sub><b>Gabriela Segura</b></sub></a><br /><a href="https://github.com/Laboratoria/bootcamp/issues?q=author%3AGabx04" title="Bug reports">🐛</a> <a href="#ideas-Gabx04" title="Ideas, Planning, & Feedback">🤔</a></td><td align="center"><a href="https://rodrwan.github.io"><img src="https://avatars3.githubusercontent.com/u/2304451?v=4" width="100px;" alt="Rod Fuenzalida"/><br /><sub><b>Rod Fuenzalida</b></sub></a><br /><a href="#ideas-rodrwan" title="Ideas, Planning, & Feedback">🤔</a></td><td align="center"><a href="https://github.com/rlazo"><img src="https://avatars1.githubusercontent.com/u/368578?v=4" width="100px;" alt="Rodrigo Lazo"/><br /><sub><b>Rodrigo Lazo</b></sub></a><br /><a href="#example-rlazo" title="Examples">💡</a> <a href="#ideas-rlazo" title="Ideas, Planning, & Feedback">🤔</a></td><td align="center"><a href="https://github.com/aldo-roman"><img src="https://avatars3.githubusercontent.com/u/497197?v=4" width="100px;" alt="Aldo Román Nureña"/><br /><sub><b>Aldo Román Nureña</b></sub></a><br /><a href="#example-aldo-roman" title="Examples">💡</a> <a href="#ideas-aldo-roman" title="Ideas, Planning, & Feedback">🤔</a></td><td align="center"><a href="https://github.com/nadiatapm"><img src="https://avatars1.githubusercontent.com/u/20929440?v=4" width="100px;" alt="Nadia Tapia"/><br /><sub><b>Nadia Tapia</b></sub></a><br /><a href="https://github.com/Laboratoria/bootcamp/issues?q=author%3Anadiatapm" title="Bug reports">🐛</a> <a href="#ideas-nadiatapm" title="Ideas, Planning, & Feedback">🤔</a></td><td align="center"><a href="https://github.com/danielasarzosa"><img src="https://avatars3.githubusercontent.com/u/29587100?v=4" width="100px;" alt="Daniela Sarzosa"/><br /><sub><b>Daniela Sarzosa</b></sub></a><br /><a href="https://github.com/Laboratoria/bootcamp/issues?q=author%3Adanielasarzosa" title="Bug reports">🐛</a> <a href="#ideas-danielasarzosa" title="Ideas, Planning, & Feedback">🤔</a></td><td align="center"><a href="https://github.com/kkatzen"><img src="https://avatars1.githubusercontent.com/u/6402808?v=4" width="100px;" alt="kkatzen"/><br /><sub><b>kkatzen</b></sub></a><br /><a href="https://github.com/Laboratoria/bootcamp/issues?q=author%3Akkatzen" title="Bug reports">🐛</a> <a href="#example-kkatzen" title="Examples">💡</a></td></tr><tr><td align="center"><a href="https://github.com/LucileBaratier"><img src="https://avatars1.githubusercontent.com/u/31043587?v=4" width="100px;" alt="LucileBaratier"/><br /><sub><b>LucileBaratier</b></sub></a><br /><a href="https://github.com/Laboratoria/bootcamp/issues?q=author%3ALucileBaratier" title="Bug reports">🐛</a></td><td align="center"><a href="https://danielalab.github.io/Daniela-Gonzales/"><img src="https://avatars0.githubusercontent.com/u/32286663?v=4" width="100px;" alt="Daniela Gonzales"/><br /><sub><b>Daniela Gonzales</b></sub></a><br /><a href="https://github.com/Laboratoria/bootcamp/issues?q=author%3ADanielalab" title="Bug reports">🐛</a> <a href="#ideas-Danielalab" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/Laboratoria/bootcamp/commits?author=Danielalab" title="Code">💻</a></td><td align="center"><a href="https://github.com/rafaelbcerri"><img src="https://avatars1.githubusercontent.com/u/11894994?v=4" width="100px;" alt="Rafael Cerri"/><br /><sub><b>Rafael Cerri</b></sub></a><br /><a href="#translation-rafaelbcerri" title="Translation">🌍</a></td><td align="center"><a href="https://github.com/josepaulolima"><img src="https://avatars1.githubusercontent.com/u/31016081?v=4" width="100px;" alt="José Paulo R. de Lima"/><br /><sub><b>José Paulo R. de Lima</b></sub></a><br /><a href="#translation-josepaulolima" title="Translation">🌍</a></td><td align="center"><a href="https://github.com/JulianaAmoasei"><img src="https://avatars3.githubusercontent.com/u/32266030?v=4" width="100px;" alt="Juliana Amoasei"/><br /><sub><b>Juliana Amoasei</b></sub></a><br /><a href="#translation-JulianaAmoasei" title="Translation">🌍</a></td><td align="center"><a href="http://www.agileandart.com"><img src="https://avatars2.githubusercontent.com/u/77552?v=4" width="100px;" alt="Daniel Cukier"/><br /><sub><b>Daniel Cukier</b></sub></a><br /><a href="#translation-danicuki" title="Translation">🌍</a></td><td align="center"><a href="https://github.com/cemsbr"><img src="https://avatars3.githubusercontent.com/u/49481?v=4" width="100px;" alt="Carlos Eduardo Moreira dos Santos"/><br /><sub><b>Carlos Eduardo Moreira dos Santos</b></sub></a><br /><a href="#translation-cemsbr" title="Translation">🌍</a></td></tr><tr><td align="center"><a href="https://github.com/vanessapinheiro"><img src="https://avatars0.githubusercontent.com/u/38503135?v=4" width="100px;" alt="Vanessa Pinheiro"/><br /><sub><b>Vanessa Pinheiro</b></sub></a><br /><a href="#translation-vanessapinheiro" title="Translation">🌍</a></td><td align="center"><a href="https://github.com/juanjordan"><img src="https://avatars1.githubusercontent.com/u/45951334?v=4" width="100px;" alt="Juan"/><br /><sub><b>Juan</b></sub></a><br /><a href="#question-juanjordan" title="Answering Questions">💬</a> <a href="https://github.com/Laboratoria/bootcamp/issues?q=author%3Ajuanjordan" title="Bug reports">🐛</a> <a href="#ideas-juanjordan" title="Ideas, Planning, & Feedback">🤔</a></td><td align="center"><a href="https://moises.dev"><img src="https://avatars0.githubusercontent.com/u/1197235?v=4" width="100px;" alt="Moisés Cachay Tello"/><br /><sub><b>Moisés Cachay Tello</b></sub></a><br /><a href="#ideas-Xpktro" title="Ideas, Planning, & Feedback">🤔</a></td><td align="center"><a href="https://www.linkedin.com/in/ilytrevino/"><img src="https://avatars0.githubusercontent.com/u/8810206?v=4" width="100px;" alt="Ily Treviño"/><br /><sub><b>Ily Treviño</b></sub></a><br /><a href="https://github.com/Laboratoria/bootcamp/issues?q=author%3Ailytrevino" title="Bug reports">🐛</a></td><td align="center"><a href="https://github.com/YolandaRib-4"><img src="https://avatars3.githubusercontent.com/u/47006006?v=4" width="100px;" alt="YolandaRib-4"/><br /><sub><b>YolandaRib-4</b></sub></a><br /><a href="https://github.com/Laboratoria/bootcamp/issues?q=author%3AYolandaRib-4" title="Bug reports">🐛</a></td><td align="center"><a href="https://github.com/carlosroec"><img src="https://avatars0.githubusercontent.com/u/1981518?v=4" width="100px;" alt="Carlos G. Rodriguez"/><br /><sub><b>Carlos G. Rodriguez</b></sub></a><br /><a href="#maintenance-carlosroec" title="Maintenance">🚧</a></td></tr></table>

<!-- ALL-CONTRIBUTORS-LIST:END -->

Este proyecto sigue la especificación de
[all-contributors](https://github.com/kentcdodds/all-contributors). Todo tipo de
contribuciones son bienvenidas.

## Licencia & Copyright

Todos los materiales de este repo son (c) 2017-2020 [Laboratoria](https://laboratoria.la/).

[![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc-nd/4.0/)

Este trabajo está publicado bajo la licencia [Creative commons
Attribution-ShareAlike 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
