# Descripción
- El ADC tiene una resolución de 10 bits.
- Es de aproximaciones sucesivas.
![](https://allday-3d.com/images/discover/arduino/arduino_uno_rev003.png)
# 
# Institucional: Laboratorio de microcontroladores
# Sección 1
  ㅤ
  
__***¿Cuántos puertos tiene el microcontrolador ATMEGA328P?***__

Tienes 3 puertos:
1.	PUERTO B
2.	PUERTO C
3.	PUERTO D

   
ㅤ

ㅤ
__***¿Cuál es la diferencia entre el microcontrolador y la tarjeta de desarrollo Arduino?***__

El microcontrolador es el puro chip que hace tareas lógicas y requiere mucho 
conocimiento de hardware y programación, aparte tiene que ser integrado en un 
circuito para funcionar, por otro lado, la tarjeta Arduino es una placa que lleva 
el microcontrolador y más componentes que se creó para facilitar su uso en proyectos.

ㅤ

ㅤ
__***¿Cuántos volts entrega cada pin de los puertos?***__

5V
ㅤ


ㅤ
__***¿Cuánta corriente entrega cada uno de los pines de los puertos del microcontrolador?***__

Puede entregar hasta 40 mA de corriente.
ㅤ

ㅤ

__***Se necesita conectar dos LEDs, para lo cual se van a utilizar los pines 0 (cero) y 7 (siete) del microcontrolador (PUERTO D), 
escribe el número en binario y hexadecimal que se le tiene que escribir al puerto para encenderlos.***__
1.	Binario: 10000001
2.	Hexadecimal: 0x81
ㅤ

ㅤ

__***¿Qué es una localidad de memoria en el microcontrolador?***__

Es donde se almacena los datos.
ㅤ

ㅤ

__***¿Cuál es la capacidad del microcontrolador para la memoria de programa?***__

32 KB
ㅤ

ㅤ

__***¿Cuál es la capacidad del microcontrolador para la memoria de datos?***__

2 KB
ㅤ

ㅤ

__***¿Cuál es la diferencia entre la arquitectura Harvard y Von Newmann?***__

Harvard separa las memorias para acelerar el acceso, mientras que Von Neumann usa una única memoria compartida.
ㅤ

ㅤ

__***¿De cuantos bits es el microcontrolador ATMEGA328P?***__

8 bits.
ㅤ

ㅤ

__***¿De cuantos bits es el ADC del microcontrolador?***__

10 bits.
ㅤ

ㅤ

#
# Sección 2
ㅤ

_Responde cierto o falso._
ㅤ

__***Se requiere controlar un motor DC, para lo cual se debe conectar directamente el motor a la tarjeta Arduino UNO para hacerlo funcionar.***__

 ㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ<s> ㅤ***CIERTO***ㅤ </s> ㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤFALSOㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤNO SE
 ㅤ

 ㅤ
 

__***Necesito conectar un LED a la tarjeta Arduino UNO, ¿es necesario forzosamente poner una resistencia a tierra?***___

ㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ<s>ㅤ***SI***ㅤ</s>ㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤNO
ㅤ

ㅤ

__***Describe los comandos del git  low básico para subir archivos al repositorio de GIT.***__
1.	$ git add: agregar archivo el repositorio.
2.	$ git commit -m “ ”: Para el registro de cambios.
3.	$ git push origin: para subir los cambios.
ㅤ

ㅤ

#
# Sección 3
ㅤ

_Reflexiona y responde las siguientes preguntas._

__***1.	¿Qué es una señal?***__

Es la magnitud de la naturaleza que se puede medir.
ㅤ

ㅤ

__***2.	¿Sería posible procesar una señal sin recurrir al muestreo?***__

No, ya que el muestreo es fundamental para convertir las señales analógicas a formato digital.
ㅤ

ㅤ

__***3.	¿Por qué se debe muestrear una señal?***__

Para convertir las señales analógicas a formato digital y poder darle un valor a la señal.
ㅤ

ㅤ

__***4.	¿Cómo relacionas el tamaño de paso del microcontrolador con los números binarios?***__

Se relacionan con los números de bits, el tamaño de paso está determinado por el número de bits del ADC. 
Valores binarios, un ADC de 10 bits puede mostrar 1024 valores binarios. 
ㅤ

ㅤ

__***5.	¿Cuál crees que sea la diferencia entre lo análogo y lo digital?***__

Que lo analógico es continuo puede tomar cualquier valor dentro de un rango y se usa para señales y lo digital es discreto que son 0 y 1.
ㅤ

ㅤ



&copy; __Alexandra Casales__
