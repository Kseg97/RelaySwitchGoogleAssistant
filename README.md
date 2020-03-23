# Relay Switch commanded by Google Assistant
Este interruptor o switch permite conectar una ESP32 con IFTTT a través de MQTT (Adafruit IO) para ser comandado por voz. El comando por voz se realiza a través de Google Assistant o Alexa.

## Introducción 🚀

Los sistemas de mando a distancia han representado una extensión a la capacidad humana con un valor elevado en ahorro de tiempo, comodidad y agilidad de procesos. Es así, como sistemas tan básicos como el control remoto, cambiaron la historia y rápidamente fueron adoptados como interfaces humano-máquina tan aceptados que ahora hacen parte de la vida cotidiana. En particular, la modernidad y el avance de la tecnología han permitido la creación de nuevas técnicas y mecanismos para comunicar comandos y controlar dispositivos de forma remota. Uno de estos mecanismos es el comando de voz. 

El comando de voz es particularmente funcional para escenarios dónde un dispositivo interruptor tradicional o “apagador” no es accesible o resulta en un esfuerzo mayor para la persona que requiere el apagado o encendido de un dispositivo. Son casos tales como el de personas con discapacidad motriz, personas de viaje o individuos con alta carga labora, que requieren el control sobre algún aparato a causa de sus limitaciones, seguridad de sus pertenencias o simple comodidad. El valor agregado parece no tener límites, según lo que denominamos como carga o dispositivo conectado al final del interruptor.

## Resumen 📋

En esta guía se presenta un dispositivo interruptor comandado por voz, basado en el microcontrolador ESP32. El sistema consume múltiples servicios web de IFTTT, Adafruit, Amazon y Google, a través de diversas librerías e interfaces web que permiten el ensamble de la lógica en línea. El comando por voz es entregado a Google Assistant o a Amazon Alexa, según facilidad del usuario o del desarrollador para proponer soluciones más complejas.

La arquitectura de este sistema es:
![Image description](https://github.com/Kseg97/RelaySwitchGoogleAssistant/blob/master/arquitectura.png)

El montaje del circuito tiene la siguiente forma:
![Image description](https://github.com/Kseg97/RelaySwitchGoogleAssistant/blob/master/esquema.jpg)

En este repositorio se encuentra la guía.
Es necesario tener instalado el soporte Arduino para la ESP32: https://github.com/espressif/arduino-esp32#installation-instructions

## Video 📢
Para  observar la puesta en funcionamiento de la práctica, se a creado un vídeo en donde se visualizan los principales detalles del sistema. Cualquier observación, retroalimentación o duda la puedes dejar en los comentarios del vídeo, si te fue de utilidad déjanos tu like.

https://youtu.be/CBme-MJ9aC8 

## Autor ✒

* **Camilo Andrés Segura** - *Trabajo Inicial* - [Usuario Github](https://github.com/kseg97)

## Expresiones de Gratitud 🎁

* Comenta a otros sobre este proyecto 📢 