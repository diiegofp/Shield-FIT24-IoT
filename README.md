# Shield FIT24-IoT
Este dispositivo fue creado para el track de IoT en el Foro de Innovación Tecnológica (FIT), evento organizado en Universidad Galileo por el laboratorio de Investigación Tesla Lab. Además, fue diseñado y ensamblado en Guatemala. Su principal objetivo es mandar datos del sensor BME680 a través de la tecnología LoRa.


# ¿Qué podemos hacer?

Desplegar información por medio de un web server o dashboard a través de LoRa. Obtener mediciones de temperatura, humedad y presión atmosférica a través del sensor BME680. Además, cuenta con 3 Neopixeles, un Buzzer para emitir algún sonido o alerta y pin headers para conectar otro dispositivo por I2C.

# Pinout


### Buzzer
Nombre | PIN 
--- | --- 
IN | 10
VDD | 5V
VSS | GND


### NPX - WS2812B
Nombre | PIN 
--- | --- 
DIN | 11
VDD | 5V
VSS | GND

### Sensor de temperatura, humedad, presión y gas  - Comunicación I2C 
BME680 | RAK4260
--- | ---
SDI 3 | SDA PA16
SCK 4 |  SCL PA17

# Licencia

Hardware License: CERN Open Hardware License Version 2.0

Software License: GNU General Public License Version 3.0

Documentation License: CC BY 4.0 International

![](/img/oshw_facts.svg)

# Contacto

Autor: Diego Iboy (diego.iboy@galileo.edu)

