# Postwork

Recuerda que tambien puedes consultar tu postwork en la App Bedu.


## 馃幆 OBJETIVOS

- Comparen el funcionamiento de JUnit y TestNG en escenarios similares.
- Analicen el funcionamiento de la ejecuci贸n en paralelo en JUnit 5 y en TestNG.


## 馃殌 DESARROLLO

Antes de comenzar con la actividad te recomendamos revisar el siguiente recurso para que comprendas que hay detr谩s de la ejecuci贸n de pruebas en paralelo utilizando JUnit 5:

### Ejecuci贸n Paralela

**Sigan las siguientes instrucciones y dividan las actividades de forma equitativa entre cada miembro del equipo:*

1. En su archivo build.grade asegurense de tener junit en su versi贸n 5.3 o superior.
2. En el mismo archivo asegurense que la configuraci贸n test luzca de la siguiente forma.


test {
    useJUnitPlatform()
    systemProperty 'junit.jupiter.execution.parallel.enabled', 'true'
}


3. Ejecuten las pruebas
4. Cambien la configuraci贸n anterior a false y observen las diferencias en los tiempos de ejecuci贸n

Para cerrar nuestro postwork, revisemos el siguiente video que realiza un benchmark de la ejecuci贸n en paralelo entre diferentes frameworks de pruebas:

驴Cu谩l tecnolog铆a es m谩s eficiente para ejecutar los tests en paralelo?


### Reflexiones finales

驴Terminaron la actividad? respondan las siguientes preguntas:

- 驴Notaron alguna diferencia en el tiempo de ejecuci贸n de las pruebas?
_________________________________________________________________________________________________________________________________________________________________________________________________________________________________

- 驴Qu茅 ventajas consideran que aporta la ejecuci贸n en paralelo?
_________________________________________________________________________________________________________________________________________________________________________________________________________________________________

- 驴Creen que existe alguna desventaja de ejecutar nuestras pruebas en paralelo?
_________________________________________________________________________________________________________________________________________________________________________________________________________________________________


隆Mucho 茅xito y reta tu potencial!
