# Back Hub_Cine_Kanako
En este repositorio se encuentra el back de la aplicación Cine_Kanako, el cuál hace una conexión con la BD sql Server en su Versión 20.2, se trabajo en conjunto con dos compañeros del programa para así apoyarnos y apr3ender en conjunto, asi mismo se revisaban errores y se corregian

# Diagrama Entidad - Relación de la BD

![image](https://github.com/user-attachments/assets/efefafa2-e752-4cd5-8fc7-288372f126a9)

# Tablas que se usan
Se obto por trabajar con 3 trablas ya que es una forma optima de usarlas, el sistema y la creatividad da para sacar muchisimas más tablas, pero por ser nuestra primera vez en la implementación de un back se obto por el uso de unicamente 3 tablas las cuales son "Usuarios, Peliculas y Series"

# Tecnología para la realización de el Back
Para poder realizar el back de nuestra aplicación se utilizo Express.js este es un entorno de trabajo para aplicaciones web para el programario Node.js, se necesita tener la ultima versión de nodejs instalada en el equipo
para arrnacar el back se debe de abrir una terminal y ejecutar el comando "node server.js", así mismo en el archivo .env se deben de poner las credenciales de la Bd de el equipo donde se ejecute las cuales son
DB_USER="User to database"
DB_PASSWORD="Password to database"
DB_DATABASE="Database name"
DB_SERVER="Server name"
PORT="Port number"

# Retrospectiva del Proyecto

| **Aspecto**                    | **Detalles**                                                                                                                                                                                                                                                                                                               |
|--------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **¿Qué Salió Bien?**           | - Se aprendio un poco sobre express js ya que nunca se había utilizado pero es algo nuevo y se ve que es de mucha utilidad para la creación de back, aí miwsmo el trabajo en equipo realizado con compañeros del mismo programa fue muy divertido ya que se aprendio en conjunto y se resolvian dudas |
| **¿Qué Puedo Hacer Diferente?** | - Se debe aprender a realizar un mejor manejo de express, así mismo el como controlar de forma correcta mis documentos y una buena administración, de igual manera el saber como hacer una conexión de back y front de manera correcta y que sea funcional, aprender a realizar autentificaciones en un login ya que es una de las partes más dificiles y complejas                    |
| **¿Qué No Salió Bien?**        | - Ya que fue la primera vez que se trabajo con express surgieron muchas dudas, incognitas y errores, se tuvo un herror 500 el cuál por más que se busco no se dio con él, sin embargo quiero mejorar en el uso del back y cambiar mejor a una implementación en C# ta que en este si se tiene un poco más de conocimiento, de igual manera se seguira aprendiendo más de express y de su funcionamiento, no se logro realizar de forma satisfactoria y correcta una buena conexión entre back y front|
