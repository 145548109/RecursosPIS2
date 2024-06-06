# RecursosPIS2
**Caso de Uso: Grupo 1 PIS**<br>
Un caso de uso es una secuencia de acciones realizadas por el sistema, que producen un resultado observable y valioso para un usuario en particular, es decir, representa el comportamiento del sistema con el fin de dar respuestas a los usuarios.<br>
Un caso de uso recoge, en un primer momento, una descripción general. Esta descripción reflejará posiblemente uno o varios requisitos funcionales del sistema o formará parte de algún requisito.
Se puede completar la descripción definiendo cuáles son las precondiciones y postcondiciones del sistema, es decir, qué condiciones deben cumplirse para que se realice un caso de uso y cuáles son aquellas condiciones que se cumplen posteriormente al caso de uso.<br>
También se pueden enumerar los diferentes escenarios del caso de uso si los tuviese y dar una breve descripción de ellos. Los escenarios son los distintos caminos por los que puede evolucionar un caso de uso, dependiendo de las condiciones que se van dando en su realización.
<details/><summary>Titulo</summary><br>
Controlar un brazo robótico para recoger basura.<br>
</details>
<details/><summary>Actores</summary><br>
Operador, Sistema de control del brazo robótico.<br>
</details>
<details/><summary>Descripción</summary><br>
El siguiente caso de uso va describir lo más detalladamente posible, como un operador (nosotros) utiliza y controla un brazo robótico que cumple con la función de recolectar basura y depositarla en un contenedor determinado, el control será realizado por medio de bluetooth.<br>
</details>
<details/><summary>Precondiciones</summary><br>
El sistema de control remoto estará cargado y funcional.<br>
El brazo robótico estará correctamente montado en el auto.<br>
El software de control Bluetooth estará correctamente instalado por lo que será funcional.<br> 
El área de operación está libre de obstrucciones y segura, en una distancia menor o igual a 10 metros.<br>
</details>
<details/><summary>Flujo Principal</summary><br>
1. El operador enciende el auto y el sistema de control del brazo robótico.<br>
2. El operador empareja el sistema con el controlador Bluetooth.<br>
3. El operador utiliza el controlador para dirigir el auto hacia el área donde se encuentra la basura.<br>
4. El operador posiciona el auto de manera que el brazo robótico pueda alcanzar la basura.<br>
5. El operador activa el brazo robótico para recoger la basura.<br>
5. El brazo robótico levanta la basura y la sostiene.<br>
6. El operador dirige el auto hacia el contenedor de basura.<br>
7. El operador deposita la basura en el contenedor.<br>
8. El operador apaga el sistema de control del brazo robótico y el auto.<br>
</details>
<details/><summary>Flujos Alternativos</summary><br>
1: Problemas de Conexión Bluetooth:<br>
El sistema no se empareja correctamente.<br>
El operador verifica y soluciona problemas de conexión.<br>
Si el problema persiste, el operador reinicia el sistema.<br>
2: Basura no Recogida Correctamente:<br>
El brazo robótico falla al recoger la basura.<br>
El operador posiciona el auto y reintenta el paso 5 del flujo principal.<br>
3: Brazo Robótico no Funciona:<br>
El operador verifica el sistema para detectar fallos.<br>
Si el problema no se puede solucionar en el campo, el operador reporta el problema para mantenimiento.<br>
</details>
<details/><summary>Documentación de requerimientos funcionales y no funcionales, separados por asignaturas</summary><br>
Emprendimiento e innovación tecnológica: Presentar en la página web un diseño convincente y atractivo del brazo robótico finalizado. El cual llamara la atención de personas que quieran adquirirlo. Con la finalidad de venderlo al mejor postor.<br>
Análisis Matemático: Calcular la velocidad constante de nuestro auto, utilizando las fórmulas adecuadas.<br>
Programación Orientada a Objetos: Mostrar un diagrama de clases que pueda ser plasmado a un código, el cual debe ser estable y libre de errores, dicho código tiene que ser entendido por cualquier persona y tener la posibilidad de ser incluido en distintos brazos robóticos.<br>
Diseño de Circuitos: Presentar un hardware atractivo y funcional, que pueda ser controlado perfectamente por el operador(nosotros).<br>
Teoría de la distribución y la probabilidad: Calcular la media de objetos recogidos y depositados en el contenedor. <br>
</details>


///
HISTORIA DE USO.

Como estudiantes de la UNL desarrollaremos esta segunda version del brazo robotico para aportar a la sostenibilidad en la sociedad. Por ende nuestro equipo debio comprender la problematica y con ello plantearnos que recursos usar. Comprendimos como podria aportar a la sociedad lojana y cómo se siente.

Queremos aportar a la sostenibilidad del medio ambiente con una segunda versión de nuestro brazo robotico. Nuestras intenciones son mejorar el funcionamiento del mismo, facilitando el control del mismo, a quien lo maneje.
//


