# Alarma con Esp32 CAM y Telegram

Proyecto con el Esp32 CAM y un sensor de movimiento que envia una imagen por Telegram cada vez que se detecte movimiento.

Video Tutorial

![esp32-cam-mini](https://user-images.githubusercontent.com/85527788/181920327-aafce7b2-05f4-45f8-89be-bc5d7b7aab70.png)

https://www.youtube.com/watch?v=WOb1QoqDoiI

## Componentes

- Esp32-Cam
- Sensor de Movimientos PIR
- Cables
- Fuente 5v

## Agregar tarjeta Esp32

Para agregar la url de la tarjeta del Esp32 debemos ir al Arduino IDE y seleccionar Archivo -> Preferencias
Luego en "Gestor de URLs Adicionales de Tarjeta" agregamos:

https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json

Si ya tenemos una url agregada previamente, ponemos la nueva con una coma ","
