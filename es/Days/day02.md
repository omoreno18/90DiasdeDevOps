---
title: '#90DaysOfDevOps - Responsabilidades de un Ingeniero DevOps - Dia 2'
published: false
description: 90DaysOfDevOps - Responsabilidades de un Ingeniero DevOps
tags: 'devops, 90daysofdevops, learning'
cover_image: null
canonical_url: null
id: 1048699
date: '2022-06-04T21:15:34Z'
---
## Responsabilidades de un Ingeniero DevOps 

Con suerte, estás entrando en esto después de revisar los recursos y publicar en [Día 1 de #90DaysOfDevOps](day01.md) 

Se mencionó brevemente en la primera publicación, pero ahora debemos profundizar en este concepto y comprender que hay dos partes principales al crear una aplicación. Tenemos la parte de **Desarrollo** donde los desarrolladores de software programan la aplicación y la prueban. Luego tenemos la parte de **Operaciones** donde la aplicación se despliega y mantiene en un servidor.

## DevOps es el enlace entre los 2 mundos

Para familiarizarnos con DevOps o las tareas que llevaría a cabo un ingeniero de DevOps, debemos comprender las herramientas o el proceso y la descripción general de los mismos y cómo se combinan.

¡Todo comienza con la aplicación! Veremos repetidamente que en todo momento, realmente, se trata de la aplicación cuando se trata de DevOps.

Los desarrolladores crearán una aplicación, esto se puede hacer con muchos stacks tecnológicos diferentes y dejemos eso a la imaginación por ahora, ya que lo introduciremos más adelante. Este montaje puede implicar muchos lenguajes de programación, herramientas de construcción, repositorios de código, etc.

Como ingenieros de DevOps, no estestaremos programando la aplicación, pero tener una buena comprensión de los conceptos, de cómo trabaja un desarrollador y los sistemas, herramientas y procesos que utilizan, es clave para el éxito.

A muy alto nivel, necesitaremos saber cómo está configurada la aplicación para hablar con todos sus servicios requeridos o sus 'data services' y luego también especificar los requisitos de cómo se puede o se debe probar esto y aquello.

La aplicación deberá desplegarse en algún lugar, seamos pragmáticos y montemos con esto un servidor, no importa dónde, pero un servidor. Esperaremos que el cliente o el usuario final acceda a todo esto dependiendo de la aplicación que se haya creado.  

Este servidor debe ejecutarse en algún lugar, on-premise , en una nube pública, serverless (está bien, quizas es volar demasiado alto, no es la intención de este challenge cubrir la tecnología serverless, pero es una opción y con la implementación de k8s es cada vez más plausible). Alguien debe crear y configurar estos servidores y prepararlos para que la aplicación se ejecute. Ahora, este elemento podría llegarnos como ingenieros de DevOps para desplegar y configurar estos servidores.

Estos servidores ejecutan un sistema operativo que, en términos generales, será Linux, pero tendremos una sección completa o semana en la que cubrimos algunos de los conocimientos fundamentales que deberemos ganar durante el reto.

También es probable que necesitemos comunicarnos con otros servicios en nuestra red o entorno, por lo que también debemos tener ese nivel de conocimiento sobre la creación de redes y la configuración, esto podría, hasta cierto punto, estar a cargo del ingeniero de DevOps. Una vez más, cubriremos esto con más detalle en una sección dedicada a hablar de todo lo relacionado con DNS, DHCP, equilibrio de carga, etc.

## Aprendiz de mucho, maestro de nada... 

Sin embargo, diré en este punto que no es necesario ser un especialista en redes o infraestructura, se necesita un conocimiento básico de cómo hacer que las cosas funcionen y se comuniquen entre sí, igual que requerimos tener un conocimiento básico de un lenguaje de programación, pero no es necesario ser un desarrollador. Sin embargo, es posible que esté entrando en esto como especialista en un área y esa es una excelente base para adaptarse a otras áreas. 

Es muy probable que tampoco nos hagamos cargo de la administración de estos servidores o de la aplicación diariamente.

Hemos estado hablando de servidores, pero lo más probable es que nuestra aplicación se despliegue para ejecutarse en contenedores, que aún se ejecutan en un servidor en su mayor parte, pero también necesitaremos comprender no solo la virtualización, sino lo que supone la infraestructura de la nube como servicio (IaaS). No debemos preocuparnos, el enfoque en estos 90 días se centrará más en los contenedores.

## Resumen de Alto-nivel

Por un lado, tenemos a nuestros desarrolladores creando nuevas características y funcionalidades (así como correcciones de errores) para la aplicación.

Por otro lado, tenemos algún tipo de entorno, infraestructura o servidores que están configurados y administrados para ejecutar esta aplicación y comunicarse con todos sus servicios requeridos.

La gran pregunta es ¿cómo incorporamos esas funciones y correcciones de errores a nuestros productos y los ponemos a disposición de los usuarios finales?

¿Cómo lanzamos nuevas versiones de la aplicación? Esta es una de las tareas principales para un ingeniero de DevOps, y lo importante aquí no es solo descubrir cómo hacer esto una vez, sino que debemos hacerlo de manera continua y automatizada, de manera eficiente con lo que ¡también debe incluir pruebas!

Aquí es donde vamos a terminar este día de aprendizaje, con suerte, ha sido provechoso. En los próximos días, profundizaremos un poco más en algunas áreas más específicas de  DevOps y luego entraremos en las secciones que profundizan en las herramientas y los procesos y los beneficios de estos.

## Recursos 

Siempre estamos abiertos a agregar recursos adicionales a estos archivos Léame, ya que están aquí como una herramienta de aprendizaje.

Mi consejo es que miremos todo lo siguiente y, con suerte, que hayamos aprendido algo del texto y las explicaciones anteriores.
- [What is DevOps? - TechWorld with Nana](https://www.youtube.com/watch?v=0yWAtQ6wYNM)
- [What is DevOps? - GitHub YouTube](https://www.youtube.com/watch?v=kBV8gPVZNEE)
- [What is DevOps? - IBM YouTube](https://www.youtube.com/watch?v=UbtB4sMaaNM)
- [What is DevOps? - AWS ](https://aws.amazon.com/devops/what-is-devops/)
- [What is DevOps? - Microsoft](https://docs.microsoft.com/en-us/devops/what-is-devops)

Si llegaste hasta aquí, sabrás si es aquí donde quieres estar o no. Te veo en el [Día 3](day03.md).  
