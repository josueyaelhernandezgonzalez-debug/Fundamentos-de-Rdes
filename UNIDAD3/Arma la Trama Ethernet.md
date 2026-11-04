Nombre: Josué Yael Hernández González

### Campo 1
- Dato de ejemplo: 10101010 10101010 10101010 10101010 10101010 10101010 10101010 10101011 (8 bytes)
- Nombre del campo: Preámbulo
- Para qué sirve: sirve para los dispositivos que se pueden conectar ala red se sincronicen a nivel físico con el reloj de la señal de transmisión

### Campo 2
- Dato de ejemplo: FFFF.FFFF.FFFF (6 bytes)
- Nombre del campo: SFD(Start Frame Delimiter)
- Para qué sirve: es un byte que funciona como una alerta para que nos indique que  la trama preámbulo ha terminado y que los datos reales de la trama están a punto de llegar

### Campo 3
- Dato de ejemplo: 0001.4321.ABCD (6 bytes)
- Nombre del campo: Dirección MAC de origen
- Para qué sirve: esta sirve para indicarnos el origen de la dirección física de la MAC que es única de la tarjeta red del dispositivos esto permite que cuando se reciba la dirección el receptor sepa quien la transmitió

### Campo 4
- Dato de ejemplo: 0x0806 (2 bytes)
- Nombre del campo: Tipo de Longitud
- Para qué sirve: nos ayuda a la especificación de la capa superior que es la capa 3 del modelo OSI. esto indica que si los datos pertenecen a IPV4,IPV6 o ARP así permitiendo que el equipo receptor sepa a que receptor o software mandar la información

### Campo 5
- Dato de ejemplo: ¿Quién tiene la IP 192.168.1.2? Responde a 192.168.1.1 (entre 46 y 1500 bytes)
- Nombre del campo: Payload
- Para qué sirve: este nos sirve para contener datos reales que se están transmitiendo los cuáles serian de la capa superior del modelo OSI

### Campo 6
- Dato de ejemplo: 0x3A7F91C2 (4 bytes)
- Nombre del campo: CRC(Cyclic Redundacy Check)
- Para qué sirve: este contiene un código de verificación de errores que son generados mediante un algoritmo matemático
