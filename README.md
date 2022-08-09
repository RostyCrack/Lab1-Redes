# Lab1-Redes
Laboratorio 1: Crear una red básica.


Juan David Martínez, Santiango Barrera y Cristian Rosero

¿Cómo permitir que Juanita Pérez y sus familiares puedan navegar por la página Web cisco.com, desde su casa, desde sus computadores personales y teléfonos celulares, utilizando una red y comunicación de datos?


Para empezar se agregan los siguientes componentes y se conectan:
<img width="1184" alt="Capture d’écran 2022-08-08 à 11 08 39" src="https://user-images.githubusercontent.com/78422799/183463181-e147712f-13c0-412d-b1ab-e78092dca204.png">


1. Configurar el servidor:

1.1. Agregar el gateway y el DNS de cisco en la sección config.
<img width="699" alt="Capture d’écran 2022-08-08 à 11 13 05" src="https://user-images.githubusercontent.com/78422799/183464015-39305323-116a-4106-96e1-d7e73dea1965.png">

1.2. Configurar el servicio DHCP para que asigne las direcciones IP correctamente:
<img width="697" alt="Capture d’écran 2022-08-08 à 11 13 14" src="https://user-images.githubusercontent.com/78422799/183464183-73422c5a-1913-40d7-b7b4-fef301bfeda5.png">

1.3. Agregar en la sección de DNS, la DNS de cisco.com junto a su nombre:
<img width="709" alt="Capture d’écran 2022-08-08 à 11 13 22" src="https://user-images.githubusercontent.com/78422799/183464403-a5bdee92-6148-464e-a92d-a020e6772b6a.png">

1.4. Se conecta el servidor con la nube por meddio de un cable de cobre.


2. Configurar la nube:

2.1. Conectar el módem por medio de un cable coaxial.
2.2. En la sección dde config buscar el puerto Ethernet donde está conectado el servidor y seleccionar cable.
<img width="703" alt="Capture d’écran 2022-08-08 à 11 16 58" src="https://user-images.githubusercontent.com/78422799/183464920-f8bf4960-0d3e-4f3a-9c50-119bd36ec7d2.png">

2.3. Seleccionar el cable coaxial para que dirija hacia el servidor.
<img width="697" alt="Capture d’écran 2022-08-08 à 11 16 52" src="https://user-images.githubusercontent.com/78422799/183465001-d19f8871-3aca-41be-980b-188e079ccfb4.png">

3. Configurar el router:
3.1. Conectar el router con el módem por medio ded un cable dde cobre.

3.2. Definir un nombre de red, la DNS y la Subnet Mask.

<img width="884" alt="Capture d’écran 2022-08-08 à 11 22 01" src="https://user-images.githubusercontent.com/78422799/183466041-cb0e1fcd-72d7-40ad-985c-86196231b745.png">

3.3. Definir el nombre de red y la clave.

<img width="823" alt="Capture d’écran 2022-08-08 à 11 22 14" src="https://user-images.githubusercontent.com/78422799/183466160-75e29fbe-7bfa-43c9-9650-7b11bf4245aa.png">

<img width="849" alt="Capture d’écran 2022-08-08 à 11 22 21" src="https://user-images.githubusercontent.com/78422799/183466179-d13e6c6f-883b-440b-9f72-bcdfe4e485b7.png">

4. Dar acceso a los dispositivos conectándolos a la red, y definiendo el protocolo DHCP para asignar la IP.

<img width="685" alt="Capture d’écran 2022-08-08 à 11 28 38" src="https://user-images.githubusercontent.com/78422799/183466981-b7554abc-6db5-4ec6-aa9d-82038b92f02a.png">

Topología de bus.
Enrutamiento de congestión de red.

Video:

https://youtu.be/rqdbtgthtOU
