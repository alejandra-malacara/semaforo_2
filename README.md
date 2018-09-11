# semaforo_2
Alejandra Malacara Avila 

practica para realizar un semaforo

Sistema alertizador salvaguarda humano-coche

Descripcion de la practica 

Realizar un sistema que simule un Semáforo Interactivo usando Arduino. Este debe mostrar un conjunto
de semáforos que cambiarán de verde a ámbar a rojo, y viceversa, luego de un período de tiempo
establecido, utilizando el sistema de cuatro estados de los semáforos en México. Este se extiende para
incluir un conjunto de luces y un botón peatonal para solicitar cruzar la calle.
Cuando llega el peatón y se dispone a cruzar pulsa el botón que encuentra en la parte baja del semáforo,
este reconoce la orden y cierra el paso de los vehículos para que el viandante pueda cruzar con seguridad
hasta el otro lado de la calle. Una vez que se acaba el tiempo estipulado para que el peatón cruce, ese
semáforo permanecerá abierto para mejorar la movilidad de los vehículos.
El sistema deberá de contener una perilla para controlar el tiempo mínimo en que el semáforo vehicular
va a durar en verde.

Material:

Protoboard

Arduino uno 

leds(rojo, amarillo, verde)

resistencias(10k, 1k, 220 ohms)

potenciometro(10k)

boton pulsador

cables 


En la practica se simulara dos semaforos uno peatonal y otro vehicular, el cual este ultimo esta 
automatizado hasta que el peaton pulse el boton el cual le permitira el paso haciendo detener al semafor
de los vehiculos, simulando los 4 estados del semaforo los cuales sera que el semaforo vehicular estara en verde
mientras en de los peatones en rojo, cuando se pulse el boton entonces parpadea 4 veces el led verde y cambia a o
amarillo despues de un tiempo el led amarillo parpadea otras cuatro veces y cambia a rojo, entonces el led verde 
del semaforo peatonal prende  
con el potenciometro podemos controlar el tiempo del led en el semafor peatonal.
