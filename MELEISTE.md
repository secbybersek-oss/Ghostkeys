**# GhostKeys 🎮💻

imagen

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


---
