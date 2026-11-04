### CAPA FISICA
es la primera capa
### PRINCIPIOS:COMPONENTES
la capa física se compone de tres elementos:
los modelos físicos(cables, conectores y dispositivos), la configuración de los datos y la señalización que los transmite. 
### PRINCIPIOS:PARAMETROS
Su desempeño se mide con tres parámetros: el ancho de banda(capacidad máxima), el rendimiento(lo que realmente se transfiere) y la latencia(el retardo en llegar).
### TIPO DE CABLE: COBRE
El cable de trenzado (UTP) transmite señales eléctricas con conector RJ-45, alcanza hasta 100 metros y es el mas usado en LAN; el trenzado reduce la interferencia.
- UTP
- FTP
- STP
- SFTP
### UTP:¿POR QUE LOS CABLES VAN EN PARES?
Los 8 hilos del UTP forman 4 pares trenzados. Cada par envía la señal con polaridad opuesta en sus hilos; la interferencia afecta a ambos por igual y el receptor la cancela al comparar los dos.
Cada par tiene un trenzado distinto para reducir la diafonia
### TIPOS DE CABLE: FIBRA OPTICA
La fibra óptica transmite pulsos de luz: llega a mayores y es inmune a la interferencia electromagnética ya que e luz, pero es mas cotosa y delicada de instalar 
### MEDIOS INALAMBRICOS
Transmite por ondas de radio(WI-FI, Bluetooth, Celular); dan movilidad, pero el medio es compartido 

### LA CAPA FISICA: SEÑALES DE COMUNICACION
Una señal es una variación de una propiedad física que representa bits: cambios de voltaje en cobre, pulsos de luz en fibra u ondas de radio en el aire. 
### SEÑALIZACION Y CODIFICACION FISICA
La codificación convierte los bits en un patrón predefinido que facilita la sincronía y la detección de errores; la señalización define como se representa ese patrón en el medio 
### CONEXION DE LA COMUNICACION 
un dispositivo se conecta mediante su tarjeta de red (NIC), un puerto, un conector y el medio; la NIC convierte los bits en la señal que el medio puede transportar
### CAPA 1 Y 2 DE ETHERNET
Ethernet (IEEE 802.3)es el estándar dominante en LAN y trabaja en dos capas: en la capa1 define medios y señalización, y en la capa 2define las trampas y las direcciones MAC

### ARP
el protocolo arp permite descubrir la dirección MAC de un dispositivo a partir de su dirección ip. Envía una petición por broadcast; solo el dueño de esa ip 

### Envenenamiento 
no verifica quien reponde: una atacante envia respuesta ARP falsa para que otros  equipos asocien su MAC con la IP  de otros dispositivos, por ejemplo la del router, y asi interceptar el trafica.
se mitiga con inspección dinámica de ARP
