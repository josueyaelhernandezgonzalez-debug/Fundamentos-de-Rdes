decide por donde reenviar usando solo la dirección MAC de la trama y su tabla de direcciones MAC trabaja dentro de una sola red (o una VLAN).

### SWITCH de capa 3
además de conmutar por MAC, puede enrutar usando la dirección ip  del paquete y su tabla de rutas, y conecta varias redes o VLAN entre si. 
### Capa 2 frente capa 3 
capa 2: lee la MAC, trabaja en una sola red 

### reemplaza a un router
No del todo: el router sigue siendo mejor para conectar con el exterior(WAN, internet) y para funciones cono NAT. EL switch de capa 3 se usa en campus y centro de datos para enrutar entre VLAN a alto velocidad. 

### Fibra óptica: ¿que es?
Es un cable de vidrio o plástico  
la luz viaja por el núcleo y revota en sus paredes por reflexión total interna, por que el revestimiento que lo rodea desvía la luz de vuelta hacia adentro.
### Partes del cable 
de adentro hacia afuera: el núcleo, que conduce la luz; el revestimiento que la mantiene dentro; del recubrimiento, que protege el vidrio; y la cubierta exterior.
### Fibra monomodo
Tiene un núcleo muy delgado (cerca de 9micras) por donde viaja un solo haz de luz, generado con laser; alcanza decenas de Kilómetros.
### Fibra multimodo
tiene un núcleo mas grueso (50 o 62.5 micras) por donde viajan varios haces a la vez, generados con LED; sirve para distancias cortas, como dentro de un edificio o con un campus.
### Monomodo frente a un multimodo
Monomodo: núcleo delgado, laser, larga distancia y mayor costo
Multimodo: núcleo grueso, LED, corta distancia, menor costo 
### Componentes de un enlace de fibra 
Se necesita el cable de fibra con conectores sus extremos y un transceptor (SFP) que convierte la señal eléctrica en luz; un convertidor de medios une equipos 
### Transceptores 
Es un modulo intercambiable que se inserta en el puerto del switch o router y convierte la señal eléctrica en luz y a luz en señal eléctrica; se elige según el tipo de fibra, distancia y la velocidad
### tipos de transceptores
Por velocidad: SFP 1 Gbps, SFP+10Gbps, SFP28 25Gbps, QSFP+40Gbps y QSFP28 100Gbps.
### ventajas de la fibra óptica
Ofrece mucho ancho de banda, llega a mayores distancias, es inmune a la interferencia electromagnética y es mas difícil de intervenir sin ser detectado.
### desventajas de la fibra óptica

Los equipos y conectores cuestan mas, la instalación y los empalmes requieren.
### donde se usa la fibra óptica

En el backbone de internet, en los cables submarinos, en los enlaces entre los edificios de un campus y en los centros de datos.
### UTP frente a fibra óptica 
UTP: señal eléctrica, hasta 100 m, económico, sensible a la interferencia.
Fibra: decenas de kilómetros, mas costosa, inmune a la interferencia.