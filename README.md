# ESP32_WEB-SERVER-AP-mode 


###  WEB SERVER GPIO
---
Este código le permite al ESP32 crear un web server que servirá un página web.

Cómo estamos en AP-mode, el ESP32 crea el access point WIFI utilizando las credenciales siguientes cualquier dispositivo se podrá conectar con el ESP32
```
const char* ssid = "ESP32-AP";
const char* password = "123456789";
```
---

Al conectarse a la red wifi creada por el esp32, este nos dará una dirección IP por el monitor serial, que debemos ingresar en el navegador. 

En la página WEB nos encontraremos con dos botones que cambian el estado de las GPIO:
```
GPIO 26
GPIO 27
```
Debemos conectar un led en cada PIN del ESP32.

---
Para finalizar debemos accionar los botones, y veremos cómo los LEDs cambiarán su estado (ON/OFF).

