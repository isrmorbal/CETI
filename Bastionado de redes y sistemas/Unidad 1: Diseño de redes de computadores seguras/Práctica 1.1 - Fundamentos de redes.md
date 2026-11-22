<h1 align="center">Práctica 1.1 - Fundamentos de redes</h1>
<p align="center"><img src="img/practica-1.1-fundamentos-de-redes.png" width="600"></p>
<br>
<p><b>Nombre: </b>Israel Moreno Ballesta</p>
<p><b>Curso: </b>CETI</p>
<p><b>Asignatura: </b>Bastionado de Redes y Sistemas</p>

# ÍNDICE

- [Ejercicio 1](#ejercicio-1)
- [Ejercicio 2](#ejercicio-2)
- [Ejercicio 3](#ejercicio-3)
- [Ejercicio 4](#ejercicio-4)
- [Ejercicio 5](#ejercicio-5)
- [Ejercicio 6](#ejercicio-6)
- [Ejercicio 7](#ejercicio-7)

## Ejercicio 1: 

### Descompón en números binarios, los siguientes números decimales

> - **7<sub>10</sub> =** 0111<sub>2</sub>
> 
> 7/2 R = 1, 3/2 R = 1, C = 1

> - **6<sub>10</sub>  =** 0110<sub>2</sub>
> 
> 6/2 R = 0, 3/2 R = 1, C = 1

> - **3<sub>10</sub> =** 0011<sub>2</sub>
> 
> 3/2 R = 1, Cociente = 1

> - **10<sub>10</sub> =** 1010<sub>2</sub>
> 
> 10/2 R = 0, 5/2 R = 1, 2/2 R = 0, C = 1

> - **172<sub>10</sub> =** 10101100<sub>2</sub>
> 
> 172/2 R = 0, 86/2 R = 0, 43/2 R = 1, 21/2 R = 1, 10/2 R = 0, 5/2 R = 1, 2/2 R = 0, C = 1

> - **192<sub>10</sub> =** 11000000<sub>2</sub>
> 
> 192/2 R = 0, 96/2 R = 0, 48/2 R = 0, 24/2 R = 0, 12/2 R = 0, 6/2 R = 0, 3/2 R = 1, C = 1

> - **255<sub>10</sub> =** 11111111<sub>2</sub>
> 
> 255/2 R = 1, 127/2 R = 1, 63/2 R = 1, 31/2 R = 1, 15/2 R = 1, 7/2 R = 1, 3/2 R = 1, C = 1

## Ejercicio 2

### Pasa a números decimales los siguientes números binarios

> - **10011101<sub>2</sub> =** 157<sub>10</sub>
> 
> 1 x 27 = 128, 1 x 24 = 16, 1 x 23 = 8, 1 x 22 = 4, 1 x 20 = 1
> 
> 128 + 16 + 8 + 4 + 1 = 157

> - **01100011<sub>2</sub> =** 99<sub>10</sub>
> 
> 1 x 26 = 64, 1 x 25 = 32, 1 x 21 = 2, 1 x 20 = 1
> 
> 64 + 32 + 2 + 1 = 99

> - **10101010<sub>2</sub> =** 170<sub>10</sub>
> 
> 1 x 27 = 128, 1 x 25 = 32, 1 x 23 = 8, 1 x 21 = 2
> 
> 128 + 32 + 8 + 2 = 170

> - **01010101<sub>2</sub> =** 85<sub>10</sub>
> 
> 1 x 26 = 64, 1 x 24 = 16, 1 x 22 = 4, 1 x 20 = 1
> 
> 64 + 16 + 4 + 1 = 85

> - **11000011<sub>2</sub> =** 195<sub>10</sub>
> 
> 1 x 27 = 128, 1 x 26 = 64, 1 x 21 = 2, 1 x 20 = 1 
> 
> 128 + 64 + 2 + 1 = 195

> - **00111100<sub>2</sub> =** 60<sub>10</sub>
> 
> 1 x 25 = 32, 1 x 24 = 16, 1 x 23 = 8, 1 x 22 = 4 
> 
> 32 + 16 + 8 + 4 = 60

## Ejercicio 3

### Pasa a números hexadecimales los siguientes números decimales

> - **4000<sub>10</sub> =** FA0<sub>16</sub>
> 
> 4000/16 R = 0, 250/16 R = 10 , C = 15

> - **7946<sub>10</sub> =** 1F0A<sub>16</sub>
> 
> 7946/16 R = 10, 496/16 R = 0, 31/16 R = 15, C = 1

> - **1347<sub>10</sub> =** 543<sub>16</sub>
> 
> 1347/16 R = 3, 84/16 R = 4, C = 5

> - **8964<sub>10</sub> =** 2304<sub>16</sub>
> 
> 8964/16 R = 4, 560/16 R = 0, 35/16 R = 3, C = 2

## Ejercicio 4

### ¿Cuál es el rango de puertos de red a los que se le conocen como puertos bien conocidos?

Los puertos de red llamados como puertos bien conocidos son del 0 al 1023.

### Comenta a que servicios de red pertenecen los siguientes puertos:

- 21 → FTP
- 22 → SSH
- 23 → Telnet
- 25 → SMTP
- 53 → DNS
- 80 → HTTP
- 194 → IRC
- 443 → HTTPS

## Ejercicio 5

### Comenta la diferencia entre direccionamiento público, direccionamiento privado, en que documento vienen definidas, que clases hay y pon ejemplos, tanto de direcciones públicas como privadas.

La diferencia entre el direccionamiento público y privado es que el público identifica a los dispositivos en internet de forma global y única, mientras que la privada se utiliza para comunicar los dispositivos dentro de una misma red LAN. Vienen definidos en el documento RFC 1918.

Las clases están divididas de la siguiente forma:
Clase A, en direcciones públicas va de la 0.0.0.0 a la 127.255.255.255, y en direcciones privadas va de la 10.0.0.0 a la 10.255.255.255
Clase B, en direcciones públicas va de la 128.0.0.0 a la 191.255.255.255, y en direcciones privadas va de la 172.16.0.0 a la 172.31.255.255
Clase C en direcciones públicas va de la 192.0.0.0 a la 223.255.255.255, y en direcciones privadas va de la 192.168.0.0 a la 192.168.255.255
Clase D, que es para direcciones multicast
Clase E, que está reservada para investigación.

Ejemplos de direcciones privadas serían por ejemplo la 192.168.1.1 que sería la IP de un router de cualquier casa, la 172.16.1.10 o 10.0.0.5 que podría ser la dirección IP de cualquier dispositivo de la red. Y ejemplos de direcciones públicas serían por ejemplo la 8.8.8.8 que es la dirección del servidor DNS de google.

## Ejercicio 6

### Supuesto práctico. Tenemos que diseñar la red de una academia. En la academia vamos a tener 6 clases, en esas clases como máximo puede haber 30 alumnos por clase. Además, tendremos dos salas más, una sala de profesores en los que se espera un máximo de 14 profesores y otra sala para secretaria y administración en las que se necesitan como máximo un total de otros 14 dispositivos para todo el personal. Para este trabajo se nos dice que se tiene que usar un direccionamiento de red de clase C.

### Realiza el diseño de la red, de la manera más óptima posible y específica en una tabla, la máscara correspondiente a cada red según su tamaño, la dirección de red, la primera dirección útil de red, la última dirección útil de red y la dirección de broadcast.

Para las clases utilizaría la máscara /27 ya que te proporciona 32 direcciones IP de las cuales se pueden utilizar 30. Y para la sala de profesores y la de secretaría y administración utilizaría la máscara /28 ya que te proporciona 16 direcciones IP de las cuales se pueden utilizar 14.

<table>
  <thead>
    <tr align="left"><th>Red</th><th>Máscara</th><th>Dirección de red</th><th>Primera útil</th><th>Última útil</th><th>Broadcast</th></tr>
  </thead>
  <tbody>
    <tr></tr>
    <tr><td>Clase 1</td><td>255.255.255.224</td><td>192.168.0.0</td><td>192.168.0.1</td><td>192.168.0.30</td><td>192.168.0.31</td></tr>
    <tr><td>Clase 2</td><td>255.255.255.224</td><td>192.168.0.32</td><td>192.168.0.33</td><td>192.168.0.62</td><td>192.168.0.63</td></tr>
    <tr><td>Clase 3</td><td>255.255.255.224</td><td>192.168.0.64</td><td>192.168.0.65</td><td>192.168.0.94</td><td>192.168.0.95</td></tr>
    <tr><td>Clase 4</td><td>255.255.255.224</td><td>192.168.0.96</td><td>192.168.0.97</td><td>192.168.0.126</td><td>192.168.0.127</td></tr>
    <tr><td>Clase 5</td><td>255.255.255.224</td><td>192.168.0.128</td><td>192.168.0.129</td><td>192.168.0.158</td><td>192.168.0.159</td></tr>
    <tr><td>Clase 6</td><td>255.255.255.224</td><td>192.168.0.160</td><td>192.168.0.161</td><td>192.168.0.190</td><td>192.168.0.191</td></tr>
    <tr><td>Sala de profesores</td><td>255.255.255.240</td><td>192.168.0.192</td><td>192.168.0.193</td><td>192.168.0.206</td><td>192.168.0.207</td></tr>
    <tr><td>Secretaría y administración</td><td>255.255.255.240</td><td>192.168.0.208</td><td>192.168.0.209</td><td>192.168.0.222</td><td>192.168.0.223</td></tr>
  </tbody>
</table>

## Ejercicio 7

Un adaptador es un componente físico o virtual que permite a un equipo conectarse a una red o a internet. Cada uno tiene una dirección MAC única.

Las opciones de configuración que ofrecen son: dirección IP, máscara y puerta de enlace ya sea estática o por DHCP, servidores DNS, MTU, velocidad y dúplex, dirección MAC, Wake on LAN, VLAN, modo promiscuo, activar/desactivar la interfaz y, en Wi-Fi, SSID y seguridad (WPA2/WPA3).

En Windows se puede configurar de varias formas:

- Configuración → Red e Internet → Ethernet/Wi-Fi
- Panel de control → Centro de redes → Cambiar configuración del adaptador (o win + r y ejecutando ncpa.cpl). Clic derecho → Propiedades → Protocolo de Internet versión 4 (TCP/IPv4) para IP, máscara, puerta de enlace y DNS. En Configurar → Opciones avanzadas están velocidad, dúplex, Wake on LAN y MAC.

Y luego desde terminal, ejecutando los siguientes comandos.

#### Para obtener información:

ipconfig
<img src="img/" width="400">

ipconfig /all
<img src="img/" width="400">

getmac
<img src="img/" width="400">

route print
<img src="img/" width="400">

arp -a
<img src="img/" width="400">

#### DHCP y DNS:

ipconfig /release
<img src="img/" width="400">

ipconfig /renew
<img src="img/" width="400">

ipconfig /flushdns
<img src="img/" width="400">

Para configurar el adaptador desde el terminal se puede hacer de la siguiente forma.
<img src="img/" width="400">
<img src="img/" width="400">
<img src="img/" width="400">
<img src="img/" width="400">

#### Desde Linux:

- Configuración → Red 

Y desde terminal ejecutando los siguientes comandos.

#### Para obtener información:

ip addr show (o también ip a)
<img src="img/" width="400">

ip link show (o también ip link)
<img src="img/" width="400">

ip route 
<img src="img/" width="400">

ethtool enp0s3
<img src="img/" width="400">

nmcli device status
<img src="img/" width="400">

ifconfig
<img src="img/" width="400">

cat /etc/resolv.conf
<img src="img/" width="400">

Para configurar el adaptador desde el terminal se puede hacer de la siguiente forma.

De forma temporal.
<img src="img/" width="400">
<img src="img/" width="400">
<img src="img/" width="400">

Y de forma permanente.
<img src="img/" width="400">
<img src="img/" width="400">
