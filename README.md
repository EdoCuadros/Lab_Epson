# Lab_Epson
Repositorio para Laboratorio realizado con Robot EPSON
Integrantes:

***Eduardo Cuadros Montealegre***

***Oscar Javier Restrepo***


## Introducción
La empresa Control de Movimiento ofreció una capacitación para los estudiantes del curso de Robótica de la Universidad Nacional de Colombia, Sede Bogotá. En ella se utilizó un robot SCARA de la marca EPSON, del modelo T6. Previo a la visita a sus instalaciones se desarrolló en el software EPSON RC, funciones de movimiento llevadas a aplicaciones prácticas de paletizado, para luego aplicarlas a la versión real del robot.

A lo largo del presente documento se muestran los pasos que se deben seguir desde el software para el desarrollo de los procedimientos y la simulación empleando el software EPSON RC. De igual manera se detalla el código ejecutado junto con los videos que muestran al robot SCARA T3 ejecutando las acciones programadas
## Objetivos
Conexión al software EPSON RC + 7.0.

Afianzar manejo del Robot Manager.

Consolidar el uso de los comandos Go, Move, Jump, Pallet y Pallet Outside, en el simulador y con el Robot.
## Desarrollo
Luego de ejecutar el software EPSON RC, se debe hacer clic en Proyecto/Cerra. De esta manera se garantiza que no se tiene ningún proyecto abierto.

Posteriormente se establece la comunicación del PC al controlador para ello se hace clic en Comunicaciones de PC a controlador 
![image](images/Epson_1.png)
Se selecciona el controlador y se hace clic en conectar
Epson_2
Ahora aparece en la parte de Conexión el nombre del controlador seleccionado. En este paso, el software se demora algo mientras reinicia el controlador
Epson_3
Se hace clic en Configuración/Configuración del sistema y se verifica que en Robots aparezca el robot seleccionado SCARA T6-602 y luego se hace clik en cerrar.
Epson_4
Posteriormente se hace clic en Simulator y nos aparece el robot en una zona de trabajo.
Epson_5
Abrimos el proyecto con el código del programa SPEL, el cual es el lenguaje de programación para los robot EPSON.
Epson_6
Nos Aparece el código desarrollado para la función main y cada una de las funciones creadas, en este caso varias de paletizado.
Epson_7
En las siguientes líneas aparece en código empleado
Ahora se compila el código
Epson_8
Se valida que se haya compilado sin errores. Esos se puede apreciar en la ventana inferior del programa
Epson_9
Se hace clic en el ícono de ejecutar y se despliega una ventana emergente en la cual podemos seleccionar la función a ejecutar. 
Epson_10
Cuando se hace clic en iniciar aparece un cuadro que dice está listo para comenzar?
Epson_11
Al hacer clic en Si se puede apreciar la simulación del robot ejecutando cada una de las acciones programadas.
Epson_12


## Videos

