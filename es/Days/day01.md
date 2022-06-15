---
title: '#90DaysOfDevOps - Introducción - Día 1'
published: true
description: 90DaysOfDevOps - Introduccion
tags: 'devops, 90daysofdevops, learning'
cover_image: null
canonical_url: null
id: 1048731
date: '2022-06-01T10:12:40Z'
---
## Introduccióm - Día 1 

Día 1 de nuestros 90 días de aventura de aprendizaje de las bases del DevOps y de las herramientas que nos ayudaran con la adquisición de la mentalidad DevOps.

Este itinerario de aprendizaje empieza para el autor (y un poco más reciente para mí) unos pocos años atras, pero su foco se centraba en ese momento alrededor de las plataformas de virtualización y las tecnologías de infraestructura basadas en la nube, se interesaba sobre todo en los conceptos de Infraestructura como Código y la administración de la configuración de las aplicaciones con Terraform y Chef (snif...). 

Retrocedamos a Marzo de 2021; el autor tuvo una magnífica oportunidad de aunar sus esfuerzos en torno a las estrategias "Cloud Native". Esto le permitió concentrarse principalmente en Kubernetes, en los principios de la cultura DevOps y en la comunidad formada alrededor de estas tecnologías. Comenzó su itinerario de aprendizaje y muy pronto se dió cuenta de que había un basto mundo más allá del conocimiento de los fundamentos de Kubernetes y Contenerización de aplicaciones y es por ello por eso mismo que comenzó a hablar con las comunidades de estas tecnologías y a aprender más y más sobre la cultura DevOps, sus herramientas y procesos, documentando sus progresos en público en algunas de esas áreas que le resultaban interesantes, y a las que dio forma en este "reto de 90 días".

En esta misma encrucijada me he encontrado yo estos últimos meses. Mi posición actual no me permite profundizar como me gustaría en los procesos y tecnologías necesarios para llegar a una posición de Ingeniero DevOps y/o SRE solvente, y por eso me he propuesto la realización de este "challenge", aportando una traducción para los compañeros que no tengan soltura con el idioma de Shakespeare, y actualizando y dando una aproximación más personal a las herramientas y procesos que en la verisón original fueron propuestos.

[Entonces... ¿Me acompañas a aprender sobre DevOps?](https://blog.kasten.io/devops-learning-curve)

## Empezemos el viaje

Si has ojeado el blog de arriba (con el google translate se entiende aceptablemente bien en español), veras que es un resumen de alto nivel del "challenge" que me he propuesto, y tengo que decir en este punto que no me considero ni de lejos un experto en ninguna de las secciones nombradas, pero es interesante conocer algunos recursos tanto gratuitos como de pago y ver las ventajas y beneficios que ambos mundos aportan.

Durante los próximos 90 días, intentaré documentar y cubrir de manera clara cada una de esas áreas básicas propuestas. Me siento a gusto integrando a los compañeros en mis movidas y por eso intento facilitarles la labor de aprendizaje de la mejor forma que se. Si te animas a realizar este viaje conmigo te invito a compartir las experiencias y recursos que vayas encontrando y seguro que podremos avanzar más y mejor ayudándonos entre todos.

Se puede ver en el readme de entrada del repositorio del proyecto que se han dividido las ideas en secciones abordables en 12 semanas más 6 días. Para estos primeros 6 días vamos a echar un vistazo a los fundamentos de DevOps en general antes de entrar en el detalle de cada una de las áreas que el "challenge" abarca. La lista no pretende ser exahustiva y de nuevo pretende ser un valioso recurso para todos aquellos que se quieran animar a aprender y/o contribuir.

Otro recurso interesante para compartir en este punto, y que creo que todo el mundo debería ojear, para tal vez ayudar a generar un mapa mental de donde estas y cuales son los intereses y posición por la que nos interesaria movernos es:

[DevOps Roadmap](https://roadmap.sh/devops)

Ya hacia tiempo que seguía la página [roadmap.sh](https://roadmap.sh), y siempre ha estado en mi lista de favoritos. Al mismo tiempo tenía la sensación de que conocer todo lo que hay se expone era muy complicado, por lo que creí que como entrante este "challenge" podría ser más adecuado, siempre teniendo en cuenta que el camino DevOps es más largo y amplio.

## Primeros Pasos - Definamos que es DevOps 

Hay muchísimos artículos, blogs y videos de Youtube que nos servirían aquí como punto de partida, pero como iniciamos este challenge de 90 días y como vamos a centrarnos en gastar alrededor de una hora al día aprendiendo algo nuevo sobre DevOps, creo que seria bueno comenzar por ver algo de "qué es DevOps" a alto nivel.

Lo primero, DevOps no es una herramienta. No lo puedes comprar, no es un SKU de software o un repositorio Open Source de GitHub que puedas descargar. Tampoco es un lenguaje de programación, ni magia negra o un arte oscuro.

DevOps es una manera de hacer las cosas inteligentemente en Desarrollo de Software. Espera... Pero si no soy desarrollador de software me tengo que la vuelta ahora mismo y no tocar este proyecto ni con un palo??? No. No del todo. Porque DevOps da a todos una combinación de Desarrollo de Software y Operaciones. El autor mencionó al principio que era más del mundo de las VMs y que normalmente se definía como del lado de Operaciones, pero viendolo en conjunto, donde tenemos compañeros con todo tipo de backgrounds, demostraremos que DevOps genera un gran beneficio a cada uno; Desarrolladores, Operadores e Ingenieros de QA. Todos pueden estudiar igualmente todas estas buenas maneras teniendo un mejor entendimiento de DevOps.

DevOps es un conjunto de practicas que ayudan a alcanzar la meta de todo este movimiento: reduciendo el tiempo entre la fase de modelado de un producto y su salida a produccoón al usuario final, o a quien sea, equipo interno o cliente.

Otra de las ideas en las que profundizaremos esta primera semana es **La Metodología Ágil**. DevOps y Met. Ágil estan siendo ampliamente adoptadas juntas para alcanzar la entrega continua de nuestras **Aplicaciones**.

La nota de alto nivel es que la mentalidad o cultura DevOps va de tratar de reducir el largo y extenso proceso de lanzamiento de software, que usualmente puede tomar años, para poder realizar ese mismo proceso lanzando releases más pequeñas y con más frecuencia. La otra clave fundamental que debemos entender aqui es la gran responsabilidad de un ingeniero DevOps para romper los grandes muros entre los diferentes equipos: Desarrolladores, Operadores y QAs.

Desde una perspectiva DevOps. **Desarrollo, Test y Despliegue** todo recae en el equipo de DevOps.

Cerramos este día resaltando es que para que esto sea lo más efectivo y eficiente posible, debemos aprovechar la **Automatización**. Lo veremos más adelante.

## Recursos

Siempre estoy abierto a agregar recursos adicionales a estos archivos Readme, ya que están aquí como una herramienta de aprendizaje.

Mi consejo es que miremos lo que aquí se recomienda y, con suerte, que también hayamos aprendido algo del texto y las explicaciones anteriores. 

- [DevOps in 5 Minutes](https://www.youtube.com/watch?v=Xrgk023l4lI)
- [What is DevOps? Easy Way](https://www.youtube.com/watch?v=_Gpe1Zn-1fE&t=43s)
- [DevOps roadmap 2022 | Success Roadmap 2022](https://www.youtube.com/watch?v=7l_n97Mt0ko)

Si llegaste hasta aquí, entonces sabrás si aquí es donde quieres estar o no. Nos vemos en el [Día 2](day02.md).

