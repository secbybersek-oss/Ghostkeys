**# GhostKeys 🎮💻
```
  ####    ##  ##    ####     ####    ######   ##  ##   ######   ##  ##    ####
 ##  ##   ##  ##   ##  ##   ##  ##     ##     ## ##    ##       ##  ##   ##  ##
 ##       ##  ##   ##  ##   ##         ##     ####     ##       ##  ##   ##
 ## ###   ######   ##  ##    ####      ##     ###      ####      ####     ####
 ##  ##   ##  ##   ##  ##       ##     ##     ####     ##         ##         ##
 ##  ##   ##  ##   ##  ##   ##  ##     ##     ## ##    ##         ##     ##  ##
  ####    ##  ##    ####     ####      ##     ##  ##   ######     ##      ####

 
```


GhostKeys es un proyecto educativo con Arduino que emula un teclado HID para demostrar técnicas de **automatización y concienciación en ciberseguridad**.  
Permite simular atajos, navegación en navegadores, y secuencias de ataque controladas en entornos de laboratorio.

---


⚠️ Nota ética
Este proyecto es solo para fines educativos.
No debe usarse en sistemas de terceros ni para ejecutar malware real.
Todas las pruebas deben hacerse en entornos controlados y con cuentas de prueba

📜 Licencia
MIT License – libre para usar, modificar y compartir con fines educativos


## 🚀 Características
- Emulación de teclas especiales: Tab, Espacio, Alt+F4, Ctrl+Tab.
- Secuencias automatizadas: abrir Edge, buscar en YouTube, escribir texto.
- Integración con joystick y OLED para menús interactivos.
- Demos educativas para mostrar riesgos de automatización.
  

---
🧠 Requisitos técnicos
- Arduino Leonardo / Micro / Pro Micro
- Joystick analógico
- Pantalla OLED I2C (SSD1306)
- Librerías: Keyboard.h, Wire.h, Adafruit_GFX.h, Adafruit_SSD1306.h

---

| Componente | Pin en Leonardo | Función |
|------------|-----------------|---------|
| OLED SDA   | D2              | I2C datos |
| OLED SCL   | D3              | I2C reloj |
| Joystick VRx | A0            | Eje X |
| Joystick VRy | A1            | Eje Y |
| Joystick SW  | D4            | Botón |

---

⚠️ USO EXCLUSIVO PARA DEMOSTRACIONES EDUCATIVAS Y AUTORIZADAS
✅ Permitido:
• 	Simulación de pulsaciones HID en entornos controlados
• 	Demostraciones de phishing ético con cuentas de prueba
• 	Captura de credenciales en laboratorios educativos
• 	Auditorías internas con consentimiento explícito
• 	Documentación visual con fotos y anotaciones técnicas
• 	Uso de joystick y OLED para navegación de menús educativos

❌ Prohibido:
• 	Uso en sistemas ajenos sin autorización
• 	Captura de credenciales reales o cuentas personales
• 	Distribución de payloads sin contexto educativo
• 	Alteración de sistemas operativos o redes externas
• 	Simulación de ataques sin señalización ética clara
• 	Uso fuera de laboratorios o entornos de prueba

## 🛠️ Instalación
1. Instala [Arduino IDE](https://www.arduino.cc/en/software).
2. Conecta tu Arduino Leonardo/Micro (compatible con HID).
3. Instala las librerías (librerias_a_descargar)
4. Copia el contenido de (código_todas_las_letras&simbolos).
5. Sube el sketch al Arduino.

---
⚠️ Nota importante para replicar GhostKeys

- Placa obligatoria con HID: El proyecto requiere un Arduino Leonardo, Micro o Pro Micro (ATmega32u4). Otras placas como UNO o Mega no funcionan para emular teclado porque no tienen USB nativo.

- Layout del teclado: Mi código está pensado para teclado Español Latinoamericano, hay símbolos y letras que no son igual al pulsarlas con el Arduino, por eso le agregue un Layout mas a mi teclado como EEUU, para que el Arduino haga un cambio de teclado y simule la pulsación correspondiente a mi código o lo que quiero que el Arduino escriba.
¡Esto funciona por que agregue una función en la programación!

- Si alguien usa otro layout (ej. US, ES España), algunos símbolos (@, |, {}, ()) pueden no salir igual.

- ![proyecto](https://github.com/user-attachments/assets/077aec37-9458-4242-b4dd-35194cb1161f)

---
REDES 

LinkedIn = [Brayan Tadino](https://www.linkedin.com/in/brayan-abrahan-tadino-urrieta-301293341/)  
GitHub = [secbybersek-oss](https://github.com/secbybersek-oss)


```
 
             .-\"\"\"-.
            /  .===.\\
           /  / 6 6 \\ \\ 
           |  \\ 0 /  | |
          |  /`---'\\ | |
          /_/  .-.  \\_\\
          /`   /   \\   `\\
         /    /_____\\    \\
        /_.-\"`  | |  `\"-._\\
        /`       | |       `\\
       /         |_|         \\
      /  H A C K I N G   E T H I C A L \\
    /_______________________________\\
 
  /* Stay curious. Learn ethically. Respect systems. */
 

 
```



