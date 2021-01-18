# Bienvenido a Classpip

[![Classpip Badge](https://img.shields.io/badge/classpip-dashboard-brightgreen.svg)](https://github.com/classpip/classpip-dashboard-dev)
[![Classpip Badge](https://img.shields.io/badge/classpip-movil--profesor-brightgreen)](https://github.com/classpip/classpip-movil-profesor-dev)
[![Classpip Badge](https://img.shields.io/badge/classpip-movil--estudiante-brightgreen)](https://github.com/classpip/classpip-movil-estudiante-dev)
[![Classpip Badge](https://img.shields.io/badge/classpip-server-brightgreen.svg)](https://github.com/classpip/classpip-server-dev)
[![Classpip Badge](https://img.shields.io/badge/classpip-API-brightgreen)](https://github.com/classpip/classpip-API-dev)
[![license](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/classpip/classpip/blob/master/LICENSE)



## ¿Qué es Classpip?

Classpip es una herramienta para introducir gamificación en el aula. La gamificación consiste en la introducción de las mecánicas típicas de los juegos en escenarios que no son juegos, para motivar a las personas a hacer cosas que quizá no tienen muchas ganas de hacer.

Con Classpip, un profesor puede introducir diferentes mecánicas de juego. Por ejemplo:

* *Juegos de puntos*: el profesor asignará puntos a sus alumnos en función de sus méritos (puntualidad, buenas calificaciones, ayudar a los compañeros, etc.). Los alumnos acumulan puntos, mejoran en el ranking y obtienen privilegios según el nivel de puntuación obtenido (poder oír música durante los exámenes, llevarse a casa el fin de semana la maleta de cosas interesantes de la profesora, etc.).
   
* *Juegos de colección*: el profesor asigna cromos de una colección a sus alumnos, en función de sus méritos. Los alumnos tratan de completar la colección y pueden intercambiar cromos entre ellos. Los cromos pueden ser de temática relacionada con la asignatura (los filósofos de la humanidad) y contener alguna información relevante (la obra más importante de cada filósofo). 
 
* *Juegos de preguntas*: el profesor plantea un conjunto de preguntas de respuesta múltiple y cada alumno debe responderlas. Gana el juego el alumno que más preguntas contesta bien.
 
Cualquiera de estos juegos pueden jugarse de manera individual o en equipo (si el profesor ha organizado antes a los alumnos en equipos). Todos los implicados (profesores y alumnos) interaccionan a través de web, o bien desde un ordenador (por ejemplo, el profesor creando una nueva colección de cromos) o desde un dispositivo móvil (por ejemplo, el profesor asignando puntos y los alumnos consultando el ranking o intercambiando cromos).
 
Aquí puede encontrarse un pequeño video demostrativo de algunas de las funcionalidades de Classpip.
 
Classpip es un proyecto colaborativo que se desarrolla a partir de las contribuciones de alumnos que realizan sus trabajos de final de grado o master incorporando nuevas funcionalidades.
 
Classpip utiliza las tecnologías más modernas para el desarrollo de aplicaciones web y apps para dispositivos móviles, tales como: angular, ionic, cordova, strongloop, loopback. También usa Git y GitHub para gestión de versiones y colaboración entre los alumnos participantes. 
 
## Organización de Classpip

![classpip-arch](https://github.com/classpip/classpip/raw/master/images/project-architecture.png)

En la actualidad Classpip se compone de 5 aplicaciones. A continuación se describen esas aplicaciones y se proporcionan los enlaces a las versiones en desarrollo de cada una de ellas.
 
* *Classpip-dashboard*: Es la aplicación web con la que, desde su ordenador, el profesor puede tomar todas las decisiones sobre configuración de los juegos (por ejemplo, crear una colección nueva) e interacción con cada juego (por ejemplo, asignar puntos a los alumnos). 
[![Classpip Badge](https://img.shields.io/badge/classpip-dashboard-brightgreen.svg)](https://github.com/classpip/classpip-dashboard-dev)

* *Classpip-movil-profesor*: Es la aplicación mediante la cual el profesor puede hacer algunas funciones que resulta apropiado hacer desde un dispositivo móvil (por ejemplo, asignar cromos a alumnos concretos o consultar el ranking del juego de puntos).
[![Classpip Badge](https://img.shields.io/badge/classpip-movil--profesor-brightgreen)](https://github.com/classpip/classpip-movil-profesor-dev)

* *Classpip-movil-estudiante*: Es la aplicación mediante la cual el alumno interacciona con el juego (por ejemplo, consulta los puntos que tiene, intercambia cromos con los compañeros o responde a las preguntas de un juego de preguntas). 
[![Classpip Badge](https://img.shields.io/badge/classpip-movil--estudiante-brightgreen)](https://github.com/classpip/classpip-movil-estudiante-dev)
  
* *Classpip-API*: Es la aplicación que ofrece al resto de aplicaciones los servicios de acceso a datos en modo API-REST  (por ejemplo, obtener la lista de juegos de un grupo, o los cromos que tiene un alumno en su álbum).
[![Classpip Badge](https://img.shields.io/badge/classpip-API-brightgreen)](https://github.com/classpip/classpip-API-dev)
 
 * *Classpip-server*: Es la aplicación que realiza tareas de notificación entre los usuarios. Por ejemplo, recibe la notificación de que un alumno ha completado un cuestionario y remite esa notificación al Dash para que refleje esa circunstancia en el listado de alumnos que participan en el juego. También realiza tareas de registro de actividad (por ejemplo, registrar la creación de grupos o de juegos).
[![Classpip Badge](https://img.shields.io/badge/classpip-server-brightgreen.svg)](https://github.com/classpip/classpip-server-dev)
  
Un TFG concreto típicamente implica modificaciones en los varias de las aplicaciones. Por ejemplo, se define un nuevo tipo de juego (o mejoras en los existentes), se crean los nuevos modelos de datos que se incorporan a la aplicación Classpip-API, se añaden las funcionalidades propias del profesor en el Classpip-dashboard y en Claspip-movil-profesor y se añaden las funcionalidades específicas para los alumnos en Classpip-movil-estudiante. Si además conviene hacer un registro de actividad o gestionar alguna notificación, hay que modificar también Classpip-server.

## Versiones de las aplicaciones
Cada una de las aplicaciones tiene versiones en producción (perfectamente funcionales) y versiones en desarrollo. 
 
Cada año se generan dos versiones en producción (una en fenrero y otra en septiembre) que denotaremos por A.M.0  (siendo A el año y M el mes). Por ejemplo, la versión 2021.2.0 estará lista en febrero de 2021 y se habrá construido a partir de las contribuciones de los alumnos que hayan hecho su TFG durante el curso académico 2020-2021 Q1 (se matricularon en septiembre de 2020 y acabaron el TFG en enero de 2021). La versión 2021.9.0 estará lista en septiembre de 2021 y se habrá construido a partir de las contribuciones de los alumnos que hayan hecho su TFG durante el curso académico 2020-2021 Q2 (se matricularon en febrero de 2021 y acabaron el proyecto en septiembre de ese mismo año). Es posible que durante el cuatrimestre se detecten algunos fallos de la versión en producción cuya resolución no pueda esperar a la nueva versión y tengan que ser resueltos inmediatamente. Eso dará luegar a nuevas versiones de producción que se etiquetarán con A.M.1, A.M.2 etc.
 
En todo momento, cada aplicación tiene también una versión en desarrollo. En esa versión van integrando sus contribuciones los alumnos que están trabajando en ese momento con la aplicación. Cuando acaba el cuatrimestre en curso (en enero o en septiembre), la versión de desarrollo ya contiene todas las contribuciones y pasa a convertirse en la nueva versión en producción. La versión en desarrollo sigue activa para que el grupo de alumnos del nuevo cuatrimestre vaya integrando en ella sus contribuciones. Los enlaces que aparecen en esta página corresponden a las versiones en desarrollo de cada uno de los módulos.

 ## Documentos de cada versión en producción
Cada versión en producción de cada aplicación tiene asociados los documentos siguientes:
*	El código (con instrucciones para su instalación)
*	El juego de pruebas que permite verificar que esa versión de módulo funciona correctamente
*	Criterios de calidad y consignas de trabajo para el módulo
*	Las funcionalidades implementadas en esa versión del módulo
*	Los desarrollos en curso que darán lugar a la nueva versión en producción del módulo.
*	Ideas para desarrollos futuros del módulo

## Contribuyentes
Al desarrollo de las aplicaciones de Classpip contribuyen alumnos haciendo sus TFG. En el momento de la matrícula del TFG (primeros de febrero y primeros de septiembre) ya han terminado los TFG del cuatrimestre anterior y ya se sabe en qué situación está cada una de las aplicaciones. Por tanto, en el momento de la matricula ya debe haber quedado claro qué alumnos van a contribuir durante el cuatrimestre que se inicia y qué va a hacer cada uno de ellos. En ese momento se elabora el documento de desarrollos en curso.
 
No obstante, los alumnos empiezan a interesarse por el proyecto con antelación (a veces incluso con meses de antelación). En el caso de alumnos de telemática, con conocimiento previo de las herramientas que se usan (será así porque han hecho la asignatura EA), se les propone como tarea preparatoria instalarse los módulos y pasarles la batería de pruebas identificando las mejoras sencillas que creen que podrían introducirse (pueden incluirse algunas de las identificadas en el documento de desarrollos futuros). Entonces se consensua una lista de mejoras sencillas que los alumnos llevan a cabo sobre la versión en desarrollo, practicando toda la mecánica de contribución a través de GitHub.
 
Para el resto de alumnos, las tareas iniciales deben consistir en hacer los [tutoriales de las herramientas de Classpip](https://www.youtube.com/playlist?list=PL64O0POFYjHqXWZgAtku2zgG-wEFxJ3xM). En función del tipo de proyecto que se haya previsto, se hará más énfasis en uno u otro bloque del tutorial. Además de hacer los tutoriales, las tareas iniciales incluyen la realización de un ejercicio sencillo para consolidar el aprendizaje del contenido de los tutoriales.

## Contribuciones
Al inicio de su trabajo, cada contribuyente se hará en su GitHub personal un fork de la versión en desarrollo de las aplicaciones en las que trabajará. De acuerdo con el profesor supervisor, irá haciendo pull requests contra la versión en desarrollo. Después de cada pull request deberá pasar la batería de pruebas para asegurar el correcto funcionamiento (normalmente, el propio contribuyente habrá ampliado la batería de pruebas de la aplicación con aquellas necesarias para probar su contribución).
 
Al finalizar su TFG debe entregar (además de la memoria):
*	La nueva versión de la batería de pruebas de las aplicaciones que haya tocado.
*	Un texto descriptivo de las cosas añadidas a las aplicaciones que haya tocado (que se incorporará al documento de funcionalidades implementadas)
*	Cosas pendientes de hacer en las aplicacions que se hayan tocado (que se incorporarán al documento de ideas para desarrollos futuros)
 
Estos elementos se presentarán en forma de anexos a la memoria del TFG.

CONTROL DE LA CALIDAD DEL CÓDIGO (DISCUTIR ESTO)
 
Una vez finalizadas e integradas todas las contribuciones de un cuatrimestre, los profesores responsables pasarán la batería de pruebas completa a la versión en desarrollo y, una vez superadas, convertirán la versión en desarrollo en nueva versión en producción. Los contribuyentes que han acabado su TFG deben comprometerse a ayudar a los profesores responsables a resolver los errores que puedan aparecer al pasar la batería de pruebas final.

## Instalación y mecánica para las contribuciones

La página principal de cada repositorio indica qué herramientas (y qué versión de cada herramienta) hay que tener instaladas y también se dan instrucciones para la instalación y puesta en marcha de la aplicación.
 
El ciclo de contribución que hay que seguir es este:

1. El alumno hace en su GitHub personal un fork del repositorio que contiene la versión de desarrollo en curso.
 
2. Se clona la aplicación en local, desde su GitHub:
```
   git clone (URL del repositorio de la aplicación en desarrollo)
```
3. Se hace la instalación de las dependencias locales (este paso solo habrá que hacerlo en la instalación inicial):
```
   npm install
```
4. El paso 2 habrá creado un remoto que conecta el repositorio  local con el repositorio en el GitHub personal. Ese remoto se llama origin. Cambiaremos el nombre para que se llame mio.
```
  git remote remane origin mio
```
 
 
5. Creamos un remoto llamado origin que conecte el repositorio en local con el repositorio de la versión en desarrollo en curso:
 

```
  git remote add origin (URL del repositorio)
```
 
6. Crea una rama dev en local para hacer allí los desarrollos:
```
  git checkout –b dev
```
 
7. Cuando tenemos listo un conjunto de cambios de la aplicación, hacemos un commit describiendolos brevemente.
```
  git add .
  git commit –m “Descripción de los desarrollos realizados”
```

 
8. Hace un push en el repositorio del GitHub personal, para que se reflejen los cambios allí.
```
  git push mio dev
```
  
En el repositorio del GitHub personal se habrá creado una rama dev con los cambios realizados
 
9. Desde la rama dev del repositorio GitHub personal hacer un pull request para integrar los cambios realizados en la versión en desarrollo en curso. Es importante asegurarse de que los cambios se integran en la rama master de la version en desarrollo. Describir claramente los desarrollos realizados. Al hacer el pull request se indicará si hay conflictos o no. Si no hay conflictos el mismo alumno puede aceptar el pull request (todos tendrán permiso para hacerlo). Si hay conflicto entonces el autor del pull request debe intentar resolver los conflictos y contectar con alguno de los profesores responsables si tiene dificultades para hacerlo.
 
10. Una vez resuelto el pull request, el alumno se trae la versión de desarrollo en curso, en la que se han integrado sus contribuciones con las de otros alumnos.
 ```
  git checkout master
  git pull origin master
```
 
 11. Es posible que al descargar la nueva versión el compilador eche en falta algún paquete que ahora sea necesario como consecuencia de los cambios introducidos por algún otro contribuyente. En ese caso se producirá un fallo de compilación y habrá que hacer de nuevo la instalación de todas las dependencias locales:
 ```
   npm install
 ```

   Ahora es necesario pasar todas las pruebas del módulo para verificar que funciona correctamente. Si hubiese que hacer alguna modificación para resolver errores, se procedería tal y como se ha indicado a partir del paso 6.
 
12. Una vez verificado que la aplicacióno funciona correctamente, hay que enviar el código al repositorio del GitHub personal:
 ```
   git push mio master
 ```
 
13. Borra las ramas dev tanto de la copia local como la del repositorio del GitHub personal
 ```
   git branch -d dev
   git push mio --delete dev
 ```

 
En el momento que quiera hacer una nueva contribución, se repite el proceso desde el paso 6.


## License

Classpip is released under the [Apache2 License](https://github.com/classpip/classpip-mobile/blob/master/LICENSE).

