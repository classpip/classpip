# Bienvenido al ecosistema Classpip


## ¿Qué es Classpip?

Classpip es una herramienta para introducir gamificación en el aula. La gamificación consiste en la introducción de las mecánicas típicas de los juegos en escenarios que no son juegos, para motivar a las personas a hacer cosas que quizá no tienen muchas ganas de hacer.

Con el ecosistema Classpip, un profesor puede introducir diferentes mecánicas de juego. Por ejemplo:

* *Juegos de puntos*: el profesor asignará puntos a sus alumnos en función de sus méritos (puntualidad, buenas calificaciones, ayudar a los compañeros, etc.). Los alumnos acumulan puntos, mejoran en el ranking y obtienen privilegios según el nivel de puntuación obtenido (poder oír música durante los exámenes, llevarse a casa el fin de semana la maleta de cosas interesantes de la profesora, etc.).
   
* *Juegos de colección*: el profesor asigna cromos de una colección a sus alumnos, en función de sus méritos. Los alumnos tratan de completar la colección y pueden intercambiar cromos entre ellos. Los cromos pueden ser de temática relacionada con la asignatura (los filósofos de la humanidad) y contener alguna información relevante (la obra más importante de cada filósofo). 
 
* *Juegos de preguntas*: el profesor plantea un conjunto de preguntas de respuesta múltiple y cada alumno debe responderlas. Gana el juego el alumno que más preguntas contesta bien.
 
Cualquiera de estos juegos pueden jugarse de manera individual o en equipo (si el profesor ha organizado antes a los alumnos en equipos). Todos los implicados (profesores y alumnos) interaccionan a través de web, o bien desde un ordenador (por ejemplo, el profesor creando una nueva colección de cromos) o desde un dispositivo móvil (por ejemplo, el profesor asignando puntos y los alumnos consultando el ranking o intercambiando cromos).
 
Aquí pueden encontrarse algunos vídeos que demuestran el funcionamiento de Classpip.  

  
[Visión general](https://www.youtube.com/watch?v=HI09jZGl8U0)     
[Juego de evaluación](http://www.youtube.com/watch?v=mrMuaXS2oko) 

 
Classpip es un proyecto colaborativo que se desarrolla a partir de las contribuciones de alumnos que realizan sus trabajos de final de grado o master incorporando nuevas funcionalidades.
 
Classpip utiliza las tecnologías más modernas para el desarrollo de aplicaciones web y apps para dispositivos móviles, tales como: angular, ionic, cordova, strongloop, loopback. También usa Git y GitHub para gestión de versiones y colaboración entre los alumnos participantes. 
 
## Organización de Classpip

![classpip-arch](https://user-images.githubusercontent.com/26624303/126349713-f3f05b96-3a47-4fa8-a638-8c631af24717.png)

En la actualidad el ecosistema Classpip se compone de 9 aplicaciones que se muestran en la figura, con una indicación de las tecnologías más importantes usadas en cada una de ellas. A continuación se describen esas aplicaciones y se proporcionan los enlaces a las versiones en desarrollo de cada una de ellas.
 
* *Classpip-dashboard*: Es una aplicación web con la que, desde su ordenador, el profesor puede tomar todas las decisiones sobre configuración de los juegos (por ejemplo, crear una colección nueva) e interacción con cada juego (por ejemplo, asignar puntos a los alumnos). 
[![Classpip Badge](https://img.shields.io/badge/classpip-dashboard-brightgreen.svg)](https://github.com/classpip/classpip-dashboard-dev)

* *Classpip-movil-profesor*: Es la aplicación mediante la cual el profesor puede hacer algunas funciones que resulta apropiado hacer desde un dispositivo móvil (por ejemplo, asignar cromos a alumnos concretos o consultar el ranking del juego de puntos).
[![Classpip Badge](https://img.shields.io/badge/classpip-movil--profesor-brightgreen)](https://github.com/classpip/classpip-movil-profesor-dev)

* *Classpip-movil-estudiante*: Es la aplicación mediante la cual el alumno interacciona con el juego (por ejemplo, consulta los puntos que tiene, intercambia cromos con los compañeros o responde a las preguntas de un juego de preguntas). 
[![Classpip Badge](https://img.shields.io/badge/classpip-movil--estudiante-brightgreen)](https://github.com/classpip/classpip-movil-estudiante-dev)  

* *Classpip-kids*: Es la aplicación especialmente diseñada para tablets, con juegos dirigidos a alumnos de menor edad (por ejemplo, creación de cuentos, colecciones de cromos, etc.).
[![Classpip Badge](https://img.shields.io/badge/classpip-kids-brightgreen)](https://github.com/classpip/classpip-kids-dev)
 
 * *Classpip-express*: Es la aplicación que permite poner en marcha algunos juegos sin necesidad de que los participantes estén registrados como alumnos en el ecosistema Classpip. Permite realizar juegos de cuestionarios preguntas pero también realizar encuestás rápidas de satisfacción, votaciones rápidas, etc.
[![Classpip Badge](https://img.shields.io/badge/classpip-express-brightgreen)](https://github.com/classpip/classpip-express-dev)
 
* *Classpip-API*: Es la aplicación que ofrece al resto de aplicaciones los servicios de acceso a datos en modo API-REST  (por ejemplo, obtener la lista de juegos de un grupo, o los cromos que tiene un alumno en su álbum).
[![Classpip Badge](https://img.shields.io/badge/classpip-API-brightgreen)](https://github.com/classpip/classpip-API-dev)
 
 * *Classpip-server*: Es la aplicación que realiza tareas de notificación entre los usuarios. Por ejemplo, recibe la notificación de que un alumno ha completado un cuestionario y remite esa notificación al Dash para que refleje esa circunstancia en el listado de alumnos que participan en el juego. También realiza tareas de registro de actividad (por ejemplo, registrar la creación de grupos o de juegos).
[![Classpip Badge](https://img.shields.io/badge/classpip-server-brightgreen.svg)](https://github.com/classpip/classpip-server-dev)
 
 * *Classpip-web*: Es la página web de difusión de Classpip. Allí puede encontrarse una descripción del ecosistema y pueden descargarse las aplicaciones instalables en los dispositivos móviles. Pueden compartirse recursos (por ejemplo, colecciones de cromos) y descargar recursos compartidos por otros. Finalmente, pueden compartirse experiencias de uso de Classpip.
[![Classpip Badge](https://img.shields.io/badge/classpip-web-brightgreen)](https://github.com/classpip/classpip-web-dev)
 
 * *Classpip-webAPI*: Es la aplicación que ofrece a Classpip-web los servicios de acceso a datos en modo API-REST (usuarios de la web, recursos compartidos, etc.).
[![Classpip Badge](https://img.shields.io/badge/classpip-webAPI-brightgreen)](https://github.com/classpip/classpip-webAPI-dev)
 
Las aplicaciones *Classpip-movil-estudiante*, *Classpip-movil-profesor* y *Classpip-kids* tienen versiones instalables en dispositivos móviles, tando Android como IOs, y también versiones accesibles directamente en le web.  

Un TFG concreto típicamente implica modificaciones en los varias de las aplicaciones. Por ejemplo, se define un nuevo tipo de juego (o mejoras en los existentes), se crean los nuevos modelos de datos que se incorporan a la aplicación Classpip-API, se añaden las funcionalidades propias del profesor en el Classpip-dashboard y en Claspip-movil-profesor y se añaden las funcionalidades específicas para los alumnos en Classpip-movil-estudiante. Si además conviene hacer un registro de actividad o gestionar alguna notificación, hay que modificar también Classpip-server.

## Versiones de las aplicaciones
Cada una de las aplicaciones tiene versiones en producción (perfectamente funcionales) y versiones en desarrollo. 
 
Cada año se generan dos versiones en producción (una en febrero y otra en septiembre) que denotaremos por A.M.0  (siendo A el año y M el mes). Por ejemplo, la versión 2021.2.0 estará lista en febrero de 2021 y se habrá construido a partir de las contribuciones de los alumnos que hayan hecho su TFG durante el curso académico 2020-2021 Q1 (se matricularon en septiembre de 2020 y acabaron el TFG en enero de 2021). La versión 2021.9.0 estará lista en septiembre de 2021 y se habrá construido a partir de las contribuciones de los alumnos que hayan hecho su TFG durante el curso académico 2020-2021 Q2 (se matricularon en febrero de 2021 y acabaron el proyecto en septiembre de ese mismo año). Es posible que durante el cuatrimestre se detecten algunos fallos de la versión en producción cuya resolución no pueda esperar a la nueva versión y tengan que ser resueltos inmediatamente. Eso dará luegar a nuevas versiones de producción que se etiquetarán con A.M.1, A.M.2 etc.
 
En todo momento, cada aplicación tiene también una versión en desarrollo. En esa versión van integrando sus contribuciones los alumnos que están trabajando en ese momento con la aplicación. Cuando acaba el cuatrimestre en curso (en enero o en septiembre), la versión de desarrollo ya contiene todas las contribuciones y pasa a convertirse en la nueva versión en producción. La versión en desarrollo sigue activa para que el grupo de alumnos del nuevo cuatrimestre vaya integrando en ella sus contribuciones.   

Los enlaces que aparecen en esta página corresponden a los repositorios de las versiones en desarrollo de cada una de las aplicaciones. En cada repositorios puede encontrarse la información necesaria para descargar el código de la aplicación correspondiente y toda la información necesaria para poder realizar contribuciones al desarrollo de esa aplicación.
  
## Aplicaciones en producción
Las versiones en producción de las diferentes aplicaciones del ecosistema Classpip están permanentemente en ejecición en una máquina alojada en las instalaciones del laboratorio de cálculo del Campus del Baix Llobregat. Puede accederse a estas aplicaciones en los enlaces siguientes:

| Aplicación        | URL         |
| ------------- |--------------|
| Dashboard     | [classpip.upc.edu:4200](http://classpip.upc.edu:4200) | 
| Movil estudiante | [classpip.upc.edu:8100](http://classpip.upc.edu:8100)      |  
| Movil profesor | [classpip.upc.edu:8102](http://classpip.upc.edu:8102)      |  
| Express | [classpip.upc.edu:8101](http://classpip.upc.edu:8101)      |  
| Kids | pendiente      |  
| Web | [classpip.upc.edu:8120](http://classpip.upc.edu:8120)    |  
 
Las aplicaciones de servicio (APIs y Server) tambien se están ejecutando en la máquina de producción pero no son accesibles desde el exterior.  
  
Las versiones instalables en dispositivos móviles para las aplicaciones *Classpip-movil-estudiante*, *Classpip-movil-profesor* y *Classpip-kids* pueden encontrarse en la web de Classpip.  


## Formas de contribución
Al desarrollo de las aplicaciones de Classpip contribuyen alumnos haciendo sus TFG/TFM. Hay tres modalidades de trabajo: individual, en pequeño grupo o SCRUM.
  
El modalidad individual es la habitual. El alumno desarrolla el trabajo individualmente de acuerdo con los objetivos establecidos con los tutores.   En la modalidad de pequeño grupo, los alumnos se asocian en grupos de 2 o 3, realizan un trabajo en equipo organizando las tareas a su gusto, aunque presentando al final memorias individuales (que probablemente tengan una buena parte en común). La presentación oral también serán conjunta. Esta modalidad es ideal para trabajar con compañeros con los que hay un buen entendimiento.  
  
En la modalidad SCRUM los alumnos se agrupan en grupos más grandes (de 4 o más), incluso aunque no hayan trabajado juntos antes (o ni siquiera se conozcan). El trabajo se desarrolla según las pautas de la metodología ágil SCRUM, avanzando por sprints. Finalmente, cada alumno presenta la memoria que describe su contribución al trabajo del grupo. La presentación final puede ser individual o en pequeños grupos de alumnos que han trabajado más estrechamente en los diferentes sprints.  

## Material para empezar
Algunos materiales tutoriales que deben facilitar el inicio del trabajo en Classpip son:
* [Tutoriales de las herramientas de Classpip](https://www.youtube.com/playlist?list=PL64O0POFYjHqXWZgAtku2zgG-wEFxJ3xM). Se trata de una colección de vídeos describiendo los aspectos esenciales de las diferentes tecnologías usadas en Classpip (Angular, Ionic, Loopback, Git, Github, etc.). En función del tipo de proyecto que se haya previsto, se hará más énfasis en uno u otro bloque del tutorial.  
  
* [Tutorial sobre cómo hacer un juego para Classpip](https://github.com/classpip/classpip/blob/master/TutorialVotacion.pdf). Muestra los pásos básicos para crear un nuevo juego (creación de los nuevos modelos de datos, creación y gestión del juego desde el Dashboard y interacción con el juego desde el movil del estudiante).
 
 Esta es la [recopilacion de todos los TFM y TFG que se han realizado hasta el momento en Classpip](https://htmlpreview.github.io/?https://github.com/classpip/classpip/blob/master/Recopilacion.htm)

## Instalación de las herramientas necesarias
Para controbuir en el desarrollo de código del ecosistema Classpip es necesario instalar las herramientas que se indican a continuación.  

#### NodeJS
Necesitas instalar NodeJS v10.13.0. Esta instalación incluye la instalación del gestor de paquetes npm.
Para verificar que has instalado la versión correcta:
```
node -v
> v10.13.0
```
#### Git y GitHub

Necesitas instalar estas herramientas para gestión de versiones y repositorio en la nube:
 
https://git-scm.com/book/en/v2/Getting-Started-Installing-Git
 
https://github.com/

Además tienes que crear una cuenta en GitHub (si no la tienes aún) en la que harás el fork de las aplicacines, para poder hacer contribuciones.
 
 
#### Native addons en Linux (Ubuntu)

```
sudo apt-get install gcc g++ make
```

#### Native addons en Windows
Deben instalarse en con permiso de administrador
```
npm install -g windows-build-tools@5.1.0
```

#### Cliente angular
Instalar también con permisos de administrador
```
npm install -g @angular/cli@7.0.6
```
#### Ionic y Cordova

Necesitarás estas dos instalaciones (haz las instalaciones con permisos de administrador).

```
npm install -g ionic@4.6.0
npm install -g cordova@8.1.2
```
Comprueba que has instalado las versiones correctas haciendo:

```
npm list -g -depth=0
```
#### Strongloop y loopback

Instala las siguientes herramientas para gestionar los modelos de datos, también con permiso de administrador:

```
npm install -g strongloop@6.0.3
npm install -g loopback-cli@5.0.0
```
## Procedimiento para realizar las contribuciones 
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

