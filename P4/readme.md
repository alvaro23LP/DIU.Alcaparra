## DIU - Practica 4

### 1. Introducción
El propósito de esta práctica es analizar la usabilidad del prototipo empleando una combinación de dos técnicas: la prueba A/B y el cuestionario SUS (System Usability Scale). Esto permitirá comparar el rendimiento de dos alternativas de diseño, además de servir como método de coevaluación para las actividades en clase.


### 2. Caso asignado
El proyecto que nos ha tocado co-evaluar es el del equipo **DIU3_13 TecladoyRatón** cuyo enlace a Github es el siguiente: [Grupo_Caso_B](https://github.com/bete2043/DIU)

Su proyecto es llamado *Foto Élite* y consiste en una aplicación de un club de fotografía en el que se imparten cursos y conocimientos sobre el mundo de la fotografía y permite a las personas poder conocer más sobre este campo. Su diseño HI-FI o mockup de su aplicación se puede hallar en el siguiente enlace a Figma: [Mockup_Caso_B](https://www.figma.com/design/dLHjxgrZM3L5WOI7Do9CoY/Guidelines-%26-Layout?node-id=77%3A830&t=JlTJYw2a5UhbiYQ6-1)

A continuación procedemos con su co-evaluación mediante la aplicación de distintos test y simulación de tareas en la aplicación para comprobar el índice de satisfacción general de los usuarios con la app.


### 3. Usuarios ficticios
Para evaluar la usabilidad hemos escogido 4 personas ficticias con características y personalidades distintas:
* Una mujer de 34 años con experiencia intermedia en internet.
* Un chico de 15 años con experiencia intermedia.
* Un hombre de 46 años con baja experiencia.
* Una mujer de 27 años muy experimentada en las tecnologías.

Las 2 primeras personas han evaluado el caso A, mientras las otras dos el caso B. Para proceder con la evaluación hemos pedido ayuda a conocidos con experiencia similiar a los usuarios ficticios para que puedieran aportarnos su feedback y ayudarnos a completar el cuestionario SUS de manera más realista para evitar sesgar los resultados. A continuación, recogemos en una tabla los usuarios ficticios escogidos para esta tarea:

![Usuarios Ficticios](2_Usuarios.png)


### 4. Eye Tracking
Para analizar el buen diseño de la interfaz y conocer que secciones captan en mayor medida la atención, hemos usado la aplicación *Gaze Recorder*. Esta nos ha permitido crear mapas de calor que muestran las zonas de la interfaz en que el usuario fija la vista un mayor tiempo.

Hemos hecho 2 test para cada caso A y B, realizando una comparación directa de los resultados dado que el estilo de la aplicación es similar en ambos casos. En este archivo se pueden consultar los resultados recogidos: [Eye Tracking](3_Eye_Tracking.pdf)


### 5. Cuestionario SUS
Para cada uno de los personajes ficticios que hemos creado, hemos completado el cuestionario SUS (*System UsabilitY Scale*). Este test lo hemos realizado con la ayuda de conocidos que han desempeñado el papel de los usuarios. Cada uno de ellos tenía una experiencia similar a la descrita para cada personaje pora dotar a los resultados de una mayor fiabilidad. Abajo se muestran los resultados de cada usuario, recogidos en una tabla de Excel:

![Cuestionario SUS](4_Cuestionario_SUS.png)

Las conclusiones que podemos sacar a partir de este cuestionario para cada caso son:

* **Cuestionario Caso A (Grupo Alcaparra)**

La media de puntuación de los dos usuarios (#01 y #02) es de 78,75. Esto indica una buena usabilidad, situándose por encima del promedio. Esto sugiere que la mayoría de los usuarios encuentran la aplicación fácil de usar y tienen una experiencia positiva. La puntuación está cerca del rango de excelencia, aunque aún hay margen para mejoras. Los usuarios probablemente recomienden la aplicación, pero sería beneficioso abordar pequeñas áreas de frustración para perfeccionar la experiencia. 

* **Cuestionario Caso B (Grupo Teclado y Ratón)**

Para el caso B los resultados han sido 62.5 y 72.5, lo cual es una calificación mediocre, de grado C, indicando que la aplicación es simplemente aceptable. La puntuación se encuentra en el rango medio, sugiriendo que la mayoría de los usuarios pueden utilizarla sin muchos problemas, aunque existen áreas que requieren mejoras. Algunas tareas son tediosas o imposibles de realizar debido a la falta de implementación, como un área de descripción detallada de los cursos de fotografía disponibles.

Con esta puntuación, los usuarios probablemente continuarán usando la aplicación, pero tienen ciertas quejas que los impiden estar completamente satisfechos. Es poco probable que recomienden la aplicación a otros debido a sus defectos. Se recomienda atender las sugerencias de los usuarios y realizar encuestas sobre la funcionalidad de la aplicación para seguir mejorándola.



### 6. Informe de usabilidad del Caso B
En este informe detallamos el análisis completo de la usabilidad de la aplicación B, *Foto Élite*. El archivo se puede consultar aquí: [Usability Report](5_Usability_Report_B.pdf)

Resumidamente, la aplicación presenta una serie de problemas que perjudican la experiencia de usuario como son los siguientes:

- **Formulario de reserva de un curso:** Los campos son algo confusos y pueden ser irrelevantes a la hora de realizar una reserva, por ejemplo, la dirección; podrían omitirse o autocompletarse de forma transparente al usuario, adquiriendo esta información del perfil del usuario y no cada vez que se realiza una reserva.

- **Accesibilidad del calendario:** No existe un acceso a un apartado de calendario en el que se visualicen de forma rápida y fácil los días en los que se realizarán los cursos. Para conocer los días en que se imparte cada curso hay que iniciar el proceso de reserva de cada curso, lo que es bastante tedioso. Como solución, podría ponerse un apartado en la barra de navegación o un subapartado dentro de la sección de cursos.

- **Información de un curso muy nula:** No existe un apartado en el que se detalle la información relativa a un curso en concreto. Esto es vital para los usuarios, pues muchos no realizarán reservas si no saben de qué trata el curso, qué actividades en concreto van a realizar, quién lo imparte, hora, lugar, precio, etc. Proponemos que antes del proceso de reserva, se muestra una pantalla de descripción del curso, con toda la información necesaria y de interés.



### 7. Conclusiones
En conclusión, en la prueba del A/B testing, nuestro Caso A (*Sazón y Tradición*), con una puntuación SUS de 78.75, demuestra buena usabilidad, mientras que el Caso B (*Foto Élite*), con 67.5, indica una experiencia aceptable pero mejorable. Los problemas principales de B incluyen un formulario de reserva confuso, dificultad para acceder al calendario y falta de información detallada sobre los cursos. Recomendamos simplificar el formulario, añadir un acceso directo al calendario y proporcionar descripciones completas de los cursos antes de la reserva. Estas mejoras, basadas en el feedback de usuarios ficticios y pruebas de Eye Tracking, facilitarán la navegación y mejorarán la satisfacción del usuario. Implementar pruebas de usabilidad continuas y encuestas ayudará a mantener y mejorar la calidad de la aplicación.

