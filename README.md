# PNI
1. ¿Qué niveles OSI son los niveles de soporte de red? 

El nivel 1 (físico), el nivel 2 (enlace), y nivel 3 (red).

2. ¿Qué niveles OSI son los niveles de soporte de usuario?

Los niveles 5 (sesión), nivel 6 (presentación) y nivel 7 (aplicación)
 
3. ¿Cómo están OSI e ISO relacionadas entre sí? 

Están relacionados porque ISO es la organización de estándares que creó el modelo de interconexión de sistemas abiertos OSI.

4. Enumere los niveles del modelo OSI. 

Desde el nivel 1 hasta el 7 son: Físico, Enlace, Red, Transporte, Sesión, Presentación y Aplicación.

5. ¿Cómo pasa la información de un nivel OSI al siguiente? 

Pasa del nivel 7 en la maquina A hasta el nivel 1 de la misma, y se envía en lujo de bits al nivel 1 de la maquina B y sube hasta el nivel 7 de la maquina B.

6. ¿Qué son las cabeceras y cola y cómo se añaden y se quitan? 

Las cabeceras o colas son datos de control que se añaden al principio o al final de un paquete de datos.
Las cabeceras se añaden en la maquina emisora en los niveles, 6 , 5 , 4, 3, 2, y en el nivel 2 se añade una cola.
Se quitan en la maquina receptora al pasar nivel por nivel, cada nivel procesa y elimina los datos que son para el.

7. ¿Cuáles son las responsabilidades del nivel físico?

Son las características físicas de las interfases y el medio, representación de los bits, tasa de datos, sincronización de los bits, configuración de la línea, topología física y los modos de transmisión.
 
8. ¿Cuáles son las responsabilidades del nivel de enlace?

Las responsabilidades del nivel de enlace son: tramado, direccionamiento físico, control de flujo, control de errores y control de acceso.
 
9. ¿Cuáles son las responsabilidades del nivel de red? 

El direccionamiento lógico y el encaminamiento.

10. ¿Cuáles son las responsabilidades del nivel de transporte?

Son el direccionamiento en punto de servicio, segmentación y reensamblado, control de conexión, control de flujo y control de errores.
 
11. El nivel de transporte crea una conexión entre el origen y el destino. ¿Cuáles son los tres eventos involucrados en la conexión? 

Los eventos involucrados son: establecimiento de la conexión, transferencia de datos y liberación de la conexión.

12. ¿Cuál es la diferencia entre una dirección de punto en servicio, una dirección lógica y una dirección física? 

Direccionamiento lógico: el direccionamiento físico proporcionado por el nivel de enlace de datos gestiona los problemas de direcciones locales si un paquete cruza la frontera
de la red es necesario tener otro tipo de direcciones para distinguir los sistemas origen de los del destino, el nivel de red añade una cabecera al paquete que viene del nivel superior que entre otras cosas incluye las direcciones lógicas del emisor y el receptor.

Punto de servicio: las computadoras suelen ejecutar a menudo varios programas al mismo tiempo por esa razón la entrega desde el origen al destino significa la entrega no solo de una pc a otra sino también desde un proceso especifico (programa de ejecución) en una pc a un proceso especifico en el otro.

Direccionamiento físico: si es necesario distribuir las tramas por distintos sistemas de la red, el nivel de enlace de datos añade una cabecera a la trama para definir la dirección física del emisor (dirección fuente) y/o receptor (dirección destino) de la trama. Si hay que enviar la trama a un sistema fuera de la red del emisor, la dirección de receptor es la dirección de dispositivo que conecta su red a la siguiente.

13. ¿Cuáles son las responsabilidades del nivel de sesión? 

El control de dialogo y la sincronización.

14. ¿Cuáles son las responsabilidades del nivel de presentación? 

Traducción, cifrado y comprensión.

15. ¿Cuál es el objetivo de la traducción en el nivel de presentación? 

Traducir la información a lujos de bits antes de transmitirla, debido a que cada computadora usa un sistema de codificación distinto.

16. Indique alguno de los servicios proporcionados por el nivel de aplicación. 

Terminal virtual de red: es una versión de un terminal físico y permite al usuario acceder a una maquina remota. Para hacerlo, la aplicación crea una emulación software de un terminal en la maquina remota.

Servicios de correo: esta aplicación proporciona las bases para el envió y almacenamiento del correo electrónico.

17. ¿Cómo se relacionan los niveles de la familia del protocolo TCP/IP con los niveles del modelo OSI?

La familia de Protocolos TCP/IP está compuesta por cinco niveles: físico, enlace de datos, red, transporte y aplicación. Los primeros cuatro niveles proporcionan estándares físicos, interfaces de red, conexión entre redes y funciones de transporte que corresponden con los cuatro primeros niveles del modelo OSI. Sin embargo, los tres modelos superiores del modelo OSI están representados en TCP/IP mediante un único nivel denominado nivel de aplicación.

18. El nivel____sesión________ decide la localización de los puntos de sincronización. 
transporte
sesión
presentación
aplicación

19. En el nivel __red________, la unidad de datos se denomina trama.

físico
enlace de datos
red
transporte
     20. Los servicios de correo y de directorio están disponibles a los usuarios de la red a través del nivel: aplicación.

enlace de datos
sesión
transporte
aplicación


     21. A medida que los paquetes de datos se mueven  de los niveles inferiores a los superiores las cabeceras: modificadas.

añadidas
eliminadas
recolocadas
modificadas
