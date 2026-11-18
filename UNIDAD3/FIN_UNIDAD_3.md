### Dirección MAC
la dirección mas es el identificador de 48 bits que tiene cada pareja de red y que sirve para identificar el origen y el destino de una trama de la LAN(capa2). 
### como se escribe la MAC
se escribe con 12 digitos hexadecimales, por ejemplo 00:1A:2B:3C:4D:5E. El formato cambia según el sistema:con guiones en Windows
### Estructura de la MAC
los primeros 24 bits(OUI) idéntica al fabricante y los últimos 24 bits los asigna el fabricante a cada tarjeta, de modo que la dirrecion es unica
### para que sirve la MAC
los switches se usan la MAC para decidir por que puerto reenviar cada trama y construyen su tabla de direcciones aprendiendo la MAC de origen
### La MAC se pude cambiar
viene gabada de fabrica en la tarjeta, pero el sistema operativo puedemodificar por software
### Unicast, multicast y broadcast
según a cuantos equipos va dirigida, una comunicación puede ser unicast (a uno), multicast(a un grupo) o broadcast(a todos).
### Unicast: de uno a uno
la trama va a uno dolo destinatario identificando por si MAC especifica; es el tipo de trafico mas común, como abrir una pagina web o copiar en archivo 
### Unicast en el switch
el switch busca la MAC de destino en su tabla de direcciones y envía la trama solo por el puerto donde esta  ese equipo; si no la conoce, la inunda por todos los puertos 
### multicast: de uno a un grupo
la trama va a un grupo de equipos que se unieron a los demas  la ignoran. en IPv4 usa direcciones 224.0.0.0 a 239.255.255.255 y MAC que empiezan con 01:00:5E.
