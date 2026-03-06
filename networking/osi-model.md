Estudios realizados el mes de Marzo 2026
El modelo de interconexión de sistemas abiertos por las siglas OSI, se refiere al modelo creado por la organizacion de normalizacion la cual permite diversos sistemas de comunicacion con ello estan los protocolos estandar agregado a esto un protocolo es un conjunto de reglas para formatear y procesar datos y el modelo OSI es considerado un lenguaje universal para las redes informaticas y este se basa en dividr el sistema en capas apiladas similar a una hamburguesa 🍔 Cada capa del modelo realiza una tarea especifica y comunica la anterior y posterior en ello se encuentran temas como los ataques de DDoS este hace que el servicio deje de funcionar normalmente ya que deniega el servicio tambien se dan Ataques de la capa de aplicacion es un tipo de comportamiento malicioso diseñado para que la capa superior del modelo donde se gestonan las solicitudes falle

En el modelo OSI vamos a ver las 7 capas explicadas para luego lograr aplicar estos conocimientos en mis estudios y proyectos (～￣▽￣)～

1. Capa Física (Physical Layer)
La capa física es la base del modelo OSI y se encarga de la transmisión real de los datos a través de medios físicos. En esta capa intervienen los componentes físicos de la red, como cables de red, conectores, switches, routers y señales inalámbricas. La información se transmite en forma de bits, es decir, una secuencia de unos y ceros que viajan mediante señales eléctricas, ópticas o de radio.
Esta capa define aspectos como el tipo de cableado utilizado, los niveles de voltaje, la velocidad de transmisión y la forma en que se representan los bits durante la comunicación.

2. Capa de Enlace de Datos (Data Link Layer)
La capa de enlace de datos se encarga de la comunicación entre dispositivos dentro de la misma red local. Su función principal es tomar los datos provenientes de la capa de red y organizarlos en estructuras llamadas tramas (frames).
Esta capa también se encarga del control de errores y del control de flujo, asegurando que los datos lleguen correctamente al dispositivo destino dentro de la red local. Además, aquí se utilizan las direcciones MAC, que identifican de manera única a cada dispositivo conectado a la red.

3. Capa de Red (Network Layer)
La capa de red es responsable de dirigir los datos entre diferentes redes. En esta capa los datos se dividen en paquetes, y se determina la mejor ruta que deben seguir para llegar a su destino.
El protocolo más importante de esta capa es IP (Internet Protocol), el cual permite identificar los dispositivos mediante direcciones IP y dirigir los paquetes a través de diferentes redes hasta alcanzar su destino final. Otros protocolos importantes de esta capa incluyen ICMP y IPsec.

4. Capa de Transporte (Transport Layer)
La capa de transporte se encarga de la comunicación de extremo a extremo entre dispositivos. Su función principal es dividir los datos en segmentos más pequeños para facilitar su transmisión y luego reensamblarlos correctamente en el dispositivo receptor.
Esta capa también controla la velocidad de transmisión y verifica que los datos lleguen completos y sin errores. Dos de los protocolos más importantes en esta capa son TCP (Transmission Control Protocol), que garantiza una transmisión confiable, y UDP (User Datagram Protocol), que permite una transmisión más rápida pero sin verificación completa de errores.

5. Capa de Sesión (Session Layer)
La capa de sesión administra el establecimiento, mantenimiento y cierre de las sesiones de comunicación entre dos dispositivos. Una sesión representa el tiempo durante el cual dos sistemas mantienen una conexión activa para intercambiar información.
Además, esta capa puede establecer puntos de control (checkpoints) durante la transmisión de datos. Esto permite que, en caso de interrupciones o fallos en la conexión, la comunicación pueda continuar desde el último punto registrado en lugar de comenzar nuevamente desde el inicio.

6. Capa de Presentación (Presentation Layer)
La capa de presentación se encarga de preparar los datos para que puedan ser interpretados correctamente por la capa de aplicación. Entre sus funciones principales se encuentran la traducción de formatos de datos, la compresión de información y la encriptación de datos.
Esta capa asegura que la información enviada por un dispositivo pueda ser comprendida por otro, incluso si utilizan diferentes formatos de representación de datos.

7. Capa de Aplicación (Application Layer)
La capa de aplicación es la capa más cercana al usuario y permite que las aplicaciones interactúen con la red. A través de esta capa, programas como navegadores web, clientes de correo electrónico o aplicaciones de transferencia de archivos pueden comunicarse con otros sistemas.
En esta capa operan protocolos ampliamente utilizados como HTTP, HTTPS, SMTP, FTP y DNS, los cuales permiten realizar acciones cotidianas como navegar por Internet, enviar correos electrónicos o acceder a servicios en línea.
