# TFM_MasterIA
Trabajo Fin Master IA

El proyecto a desarrollar consiste en diseñar una interfaz para un reproductor multimedia, para entorno web, que sea capaz de reconocer un pequeño conjunto de gestos realizados por el usuario con una mano, a través de un microcontrolador (arduino y/o raspberry) y convertir esa captura de los citados gestos en la orden pertinente para el reproductor multimedia.

Se va a utilizar un microcontrolador Raspberry Pi Pico y otro Arduino Nano 33 BLE Sense, los cuales tienen la posibilidad de trabajar con las librerias TensorFlow LT.

Los datasets se recogerán y volcarán sobre la herramienta web Edge Impulse.(https://studio.edgeimpulse.com/studio/108222)
Se desarrollará el código usando Python (o MicroPython si fuera necesario).

El dataframe en formato csv contiene la información del dataset para arrancar con la fase de preprocesado de datos.

El fichero zip contiene los datos en bruto, una vez obtenidas las señales correspondientes a todas las muestras recogidas a través del prototipo.
