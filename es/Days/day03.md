---
title: '#90DaysOfDevOps - Centrados en la aplicación - Día 3'
published: false
description: 90DaysOfDevOps - Centrados en la aplicación
tags: 'devops, 90daysofdevops, learning'
cover_image: null
canonical_url: null
id: 1048825
---
## Ciclo de vida de DevOps: centrados en la aplicación

A medida que avancemos durante las próximas semanas, nos familiarizaremos al 100 % con estos conceptos (Desarrollo continuo, Pruebas, Implementación, Monitoreo) una y otra vez. Si en verdad queremos dirigirnos hacia el rol de Ingeniero DevOps, entonces la repetibilidad será algo que debemos tener muy presente e ir mejorando constantemente.

En esta hora, vamos a echar un vistazo de alto nivel a la aplicación de principio a fin y luego repetimos el ciclo en un bucle constante.

### Desarrollo
Tomemos un nuevo ejemplo de una Aplicación, para empezar no tenemos nada creado, tal vez como desarrolladores, deberiamos discutir con nuestro cliente o usuario final los requisitos y proponer algún tipo de plan o requerimientos para nuestra Aplicación. Luego necesitamos crear a partir de los requisitos nuestra nueva Aplicación.

En lo que respecta a las herramientas en esta etapa, no hay ningún requisito real aparte de elegir nuestro IDE y el lenguaje de programación que deseamos usar para escribir la Aplicación.

Como ingenieros de DevOps, recuerda que probablemente no seamos quienes creemos este plan o codifiquemos la aplicación para el usuario final, normalmente lo hará un desarrollador experto o un grupo de trabajo.

Pero tampoco nos vendría mal poder leer parte del código para que podamos tomar las mejores decisiones de infraestructura para la Aplicación.

Anteriormente mencionamos que esta Aplicación se puede escribir en cualquier lenguaje. Es importante que esto se mantenga usando un sistema de control de versiones o CVS, esto es algo que también cubriremos en detalle más adelante y, en particular, sucumbiremos a los placeres de **Git**.

También es probable que no haya exclusivamente un desarrollador trabajando en este proyecto, por lo que seguir las mejores prácticas requeriría un repositorio de código para almacenar y colaborar en el código, este podría ser privado o público y podría estar alojado en abierto o en privado. Hoy día suenan muchísimo **GitHub o GitLab** como repositorios de código. Los cubriremos como parte de nuestra sección sobre **Git** más adelante.

### Testeo 
En esta etapa, estamos siguiendo nuestros requisitos y nuestra Aplicación está siendo desarrollada. Pero debemos asegurarnos de que estamos probando nuestro código en todos los diferentes entornos que esten disponibles para nosotros o, específicamente, los que se hayan definido para el lenguaje de programación elegido.

Esta fase permite que los compañeros de QA realicen pruebas en busca de errores; cada vez con más frecuencia, vemos que se utilizan contenedores para simular el entorno de prueba, lo que en general puede mejorar los gastos generales y la complejidad de la infraestructura física o en la nube.

Es probable que esta fase también se automatice como parte de la siguiente área, que es la integración continua.

La capacidad de automatizar estas pruebas frente a 10, 100 o incluso miles de ingenieros de QA que debieran hacer esto manualmente, habla por sí sola; estos ingenieros pueden concentrarse en otra cosa dentro del stack para asegurarse de que nos estamos moviendo más rápido y desarrollando más funciones en lugar de andar probando errores y el software de punta a punta, que es lo que causa el retraso en la mayoría de las versiones de software tradicionales que utilizan una metodología de cascada.

### Integración

Es muy importante que la integración se encuentre en el centro del ciclo de vida de DevOps. Es la práctica en la que los desarrolladores requieren realizar cambios en el código fuente con mayor frecuencia. Estos cambios podrían añadirse diaria o semanalmente.

Con cada commit, nuestra Aplicación puede pasar por las fases de prueba automatizadas y esto permite la detección temprana de problemas o errores antes de la siguiente fase.

Ahora, en esta etapa, podríamos estar diciendo "pero si no creamos aplicaciones, las compramos listas para usar de un proveedor de software". Y que mas da, no estamos inventando la rueda, muchas empresas hacen esto y continuarán haciéndolo y será el proveedor de software el que se concentre en las 3 fases anteriores, pero es posible que desee controlar las integraciones en la fase final, ya que esto nos permitirá implementaciones más rápidas y eficientes que sus implementaciones listas para usar.

Debemos poner en valor que tener este conocimiento completo es muy importante, ya que podríamos comprar software estándar hoy, pero ¿qué pasa mañana o más adelante... el próximo trabajo tal vez?

### Despliegue

Ok, tenemos nuestra Aplicación construida y probada con los requisitos de nuestro usuario final y ahora debemos seguir adelante y desplegar esta aplicación en producción para que nuestros usuarios finales la consuman.

Esta es la etapa donde el código se despliega en los servidores de producción, ahora aquí es donde las cosas se ponen extremadamente interesantes y es en estas áreas donde el resto de nuestros 86 días profundizan. Porque diferentes aplicaciones requieren posiblemente diferentes configuraciones y hardware. Aquí es donde la **Administración de Configuraciones** y la  **Infraestructura como Código** podrían desempeñar un papel clave en nuestro ciclo de vida DevOps. Puede ser que nuestra Aplicación esté **Contenerizada** pero también disponible para ejecutarse en una máquina virtual. Esto nos lleva irremediablemente a plataformas como **Kubernetes** que se encargarían de orquestar esos contenedores y asegurarse de que tengan el estado deseado disponible para nuestros usuarios finales.

De estos temas en negrita, entraremos en más detalles en las próximas semanas para obtener el mejor conocimiento básico de lo que son y cuándo usarlos. 

### Monitoreo

Las cosas se están moviendo rápido en este momento y tenemos nuestra Aplicación que estamos actualizando continuamente con nuevas características y funcionalidades y tenemos nuestras pruebas para asegurarnos de que no se encuentren "cosas raras". Tenemos la aplicación ejecutándose en nuestro entorno que se asegura de mantener continuamente la configuración y el rendimiento requeridos.

Pero ahora debemos asegurarnos de que nuestros usuarios finales tengan la experiencia que necesitan. Aquí debemos asegurarnos de que el rendimiento de la Aplicación se monitoree continuamente, esta fase permitirá a nuestros desarrolladores tomar mejores decisiones sobre los cambios de la aplicación en futuras versiones.

En esta sección es donde también vamos a capturar ese feedback sobre las funciones que se han implementado y cómo les gustaría a los usuarios finales mejorarlas.

La confiabilidad (reliability) también es un factor clave aquí, al fin y al cabo queremos que nuestra aplicación esté disponible todo el tiempo que sea necesario. Conseguir esto nos conduce a estudiar otras áreas sobre **observabilidad, seguridad y gestión de datos** que nos obligan a llevar un monitoreo continuo dándonos pistas  que se pueden usar para mejorar, actualizar y lanzar la aplicación de manera continua.

Creo que también es un buen momento para volver a sacar el rol de "Ingeniero de DevOps" mencionado anteriormente, aunque hay muchos puestos de Ingeniero de DevOps en el día a día que la gente postula y ocupa, esta no es la forma ideal de implementar los procesos de DevOps. A lo que vamos es que, el título de ingeniero de DevOps no debería ser el objetivo para ninguna organización porque, en realidad, sea cual sea puesto que se ocupe, se deberían adoptar los procesos de DevOps y la cultura que aquí estamos explicando. DevOps debe usarse en muchos puestos diferentes, como ingeniero/arquitecto Cloud-Native, Virtualisation admin, arquitecto/ingeniero Cloud y administradores de infraestructura. Y esto es por nombrar algunos, pues la razón para usar el rol de Ingeniero DevOps arriba fue realmente para resaltar el alcance del proceso utilizado por cualquiera de los puestos anteriores y más.

## Recursos 

Siempre estoy abierto a agregar recursos adicionales a estos archivos Léame, ya que están aquí como una herramienta de aprendizaje.

Mi consejo es que mire todo lo siguiente y, con suerte, también hayamos aprendido algo del texto y las explicaciones anteriores.

- [Continuous Development](https://www.youtube.com/watch?v=UnjwVYAN7Ns) I will also add that this is focused on manufacturing but the lean culture can be closely followed with DevOps. 
- [Continuous Testing - IBM YouTube](https://www.youtube.com/watch?v=RYQbmjLgubM)
- [Continuous Integration - IBM YouTube](https://www.youtube.com/watch?v=1er2cjUq1UI)
- [Continuous Monitoring](https://www.youtube.com/watch?v=Zu53QQuYqJ0)
- [The Remote Flow](https://www.notion.so/The-Remote-Flow-d90982e77a144f4f990c135f115f41c6)
- [FinOps Foundation - What is FinOps](https://www.finops.org/introduction/what-is-finops/)
- [**NOT FREE** The Phoenix Project: A Novel About IT, DevOps, and Helping Your Business Win](https://www.amazon.com/Phoenix-Project-DevOps-Helping-Business/dp/1942788290/)

Si llegaste hasta aquí, sabrás si es aquí donde quieres estar o no. Nos vemos el [Día 4](day04.md).  
