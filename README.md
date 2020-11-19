# Chat Cliente-Servidor con Fondo
En esta programa mostraremos cómo hacer un chat
mediante el uso de Sockets en Java. 
Los Sockets sirven para comunicar procesos de diferentes máquinas de una red.

Haremos un servidor y un cliente utilizando Sockets: 
-- Del lado del Servidor se tiene un bucle infinito que espera conexiones de clientes. Cuando un 
cliente se conecta el servidor acepta la conexión y genera al menos dos threads: uno para enviar 
datos y el otro para recibirlos. 
-- Del lado del Cliente se tiene que esperar un Servidor para poder conectarse, cuando se conecta
al servidor se generan dos threads, al igual que en el Servidor uno para enviar y otro para
recibir los datos. 

La clase principal del Servidor es idéntica a la clase principal del cliente; la
única diferencia esta en el main, el servidor espera conexiones del cliente y el cliente busca
servidor para conectarse.

### Inicio
Para el buen funcioanamiento del programa es ncesario ejecutar las dos clases PrincipalChat, primero la del paquete Servidor y despues 
la del paquete Cliente, ya que si lo vemos de una forma realistica el Servidor siempre estara a la espera del cliente.
Al moemnto de ejecutar la del ciente, se creara una pequeña interfaz en la cual se tendra que agregar un nombre, el cual se vera reflejada 
en la ventana tanto del servidr y el cliente mismo cada que se escriba en los chats.

### Pre-requisitos
Para la ejecución de este programa es necesaria descargar todos los paquetes y de preferencia usar un IDE ya que es muy facil descargar el ZIP 
e importar todo el proyecto.


### Instalación 

_Basta con descargar el proyecto como Zip o con el mismo CMD, y ejecutarlo como normalmnete ejecutas un archivo tipo JAVA, ya sea con un IDE, etc.

**La clase "  PrincipalChat " es la contenedora del main para la ejecucion de todo el programa, claro en diferemte paquete existe una.


### Ejemplo de como se veria toda la paqueteria del programa con sus clases:

![image](https://user-images.githubusercontent.com/70773749/99705601-8ebddf80-2a5f-11eb-83c9-4d04acf4bd26.png)

### Ejemplo de la ejecucion del programa
1. Pequeña interfaz para asiganr un nombre al cliente


![image](https://user-images.githubusercontent.com/70773749/99706819-40a9db80-2a61-11eb-82ec-6f0350af78a3.png)



2. Ambos chats CLiente-Servidor abiertos



![image](https://user-images.githubusercontent.com/70773749/99706456-b3668700-2a60-11eb-806a-f8f9f74e7f8f.png)


## Construido con 

_IDE JAVA NEAT BEANS_



## Versionado 
Version 1.0


## Autores 

Castro Luna Ramses Uriel


## Expresiones de Gratitud 
Gracias a la busqueda de diferentes fuentes como lo fueron foros y mismos compañeros se lo gro crear este programam. 
. 
