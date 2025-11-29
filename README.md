```markdown
1| **# GhostKeys 🎮💻
2| 
3| |    _____ _    _  ____   _____ _______ _  __________     _______ 
4| |  / ____| |  | |/ __ \ / ____|__   __| |/ /  ____\ \   / / ____|
5| | |  __| |__| | |  | | (___    | |  | ' /| |__   \ \_/ / (___  
6| | | | |_ |  __  | |  | |\___ \   | |  |  < |  __|   \   / \___ \ 
7| | | |__| | |  | | |__| |____) |  | |  | . \| |____   | |  ____) |
8| |  \_____|_|  |_|\____/|_____/   |_|  |_|\_\______|  |_| |_____/ 
9| 
10| ![1](https://github.com/user-attachments/assets/1760155a-4c47-47bb-8239-2df32c53d2ae)
11| 
12| 
13| 
14| GhostKeys es un proyecto educativo con Arduino que emula un teclado HID para demostrar técnicas de **automatización y concienciación en ciberseguridad**.  
15| Permite simular atajos, navegación en navegadores, y secuencias de ataque controladas en entornos de laboratorio.
16| 
17| ![proyecto](https://github.com/user-attachments/assets/888e9bf7-c8d7-478e-85db-872031558af1)
18| 
19| 
20| ---
21| 
22| ⚠️ Nota ética
23| Este proyecto es solo para fines educativos.
24| No debe usarse en sistemas de terceros ni para ejecutar malware real.
25| Todas las pruebas deben hacerse en entornos controlados y con cuentas de prueba
26| 
27| 📜 Licencia
28| MIT License – libre para usar, modificar y compartir con fines educativos
29| 
30| 
31| ## 🚀 Características
32| - Emulación de teclas especiales: Tab, Espacio, Alt+F4, Ctrl+Tab.
33| - Secuencias automatizadas: abrir Edge, buscar en YouTube, escribir texto.
34| - Integración con joystick y OLED para menús interactivos.
35| - Demos educativas para mostrar riesgos de automatización.
36| 
37| ---
38| 
39| ## 🛠️ Instalación
40| 1. Instala [Arduino IDE](https://www.arduino.cc/en/software).
41| 2. Conecta tu Arduino Leonardo/Micro (compatible con HID).
42| 3. Instala las librerías (librerias_a_descargar)
43| 4. Copia el contenido de (código_todas_las_letras&simbolos).
44| 5. Sube el sketch al Arduino.
45| 
46| ---
47| ⚠️ Nota importante para replicar GhostKeys
48| 
49| - Placa obligatoria con HID: El proyecto requiere un Arduino Leonardo, Micro o Pro Micro (ATmega32u4). Otras placas como UNO o Mega no funcionan para emular teclado porque no tienen USB nativo.
50| 
51| - Layout del teclado: Mi código está pensado para teclado Español Latinoamericano, hay símbolos y letras que no son igual al pulsarlas con el Arduino, por eso le agregue un Layout mas a mi tec[...]
52| ¡Esto funciona por que agregue una función en la programación!
53| 
54| - Si alguien usa otro layout (ej. US, ES España), algunos símbolos (@, |, {}, ()) pueden no salir igual.
55| 
56| 
57| ---
58| 
59| @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
60| @@@@@@@@@@%%@@%@@@@@@@@@@@@@@@@@@%%%@%%%%%%@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
61| @@@@@@@@@@@@@@@@@@@@@@@@@@@#+...           ...+#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
62| @@@@@@@@@@@@%@@@%@@%@@@@%%:                     :%@@%@@%@@@%@@@@@@@@@@@@@@@@@@@@
63| @@@@@@@@@@@@@@@@@@@@@@@@@              .          @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
64| @@@@@@@@%@@%@@@%@@@@@@%%+   =+++++.  .  .+++++=   +@@%%@@@@%@@@@@@@@@@@@@@@@@@@@
65| @@@@@@@@@@@@@@@@@@@@@@@@..@@@@@@@@@.    @@@@@@@@@..@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
66| @@@@@@@@@%@@%%@@@@@@@@@@..@@@@@-*@@ .-. @@*-@@@@@..@@@%@@@@@@@@@@@@@@@@@@@@@@@@@
67| @@@@@@@@@@@@@@@@@@@%%@%@@..-%@@@@+..#@#..+@@@@%=. @@@%@@@@@@@@@@@@@@@@@@@@@@@@@@
68| @@@@@@@@%@@%@@%@@%@@%%@%%#. ...@+  .@@@.  +@... .%@%%@%@%%%@@%@@@@@@@@@@@@@@@@@@
69| @@@%@@@@@@@%@@%@@%@@%%@%%.:+@#*+==========-=@*@#:.@%%@%@@@%@@@@@@@@@@@@@@@@@@@@@
70| @@@@@@@@@@@@@@%@%%@%@%%%%#. :#%#+=@:=*..%.+-.@. .#@#::%@@@%@@@@@@@@@@@@@@@@@@@@@
71| @@@@@@@@%@@@@@%@%@@%@* .#@@#-.  =%%%%%%%%%%-..:+@%. .*@@@@%@@@@@@@@@@@@@@@@@@@@@
72| @@@@@@@@@@@%%@%@@%@%=@@@++:+%@@%++.     .-+#@@@@+..*@@@@*#@@@@@@@@@@@@@@@@@@@@@@
73| @@@@@%@@@@@%@@%@@@#%@@@@@@@= ::@%@@::::@:@%%@:..*%@@@=@@@+#@@@@@@@@@@@@@@@@@@@@@
74| @@@@@@@@@@@@@@@@%#%@@@@@@@@@@@.-:+%#--=@@+..+*@@@@@@+#@@@@+#@@@@@@@@@@@@@@@@@@@@
75| @@@@@%@@@%@@@@@@#@@@@@@@@@@@@@.@+#@*   @@-@-@@@@@@@++#@@@@@#:@@@@@@@@@@@@@@@@@@@
76| @@@@@@@@@@@@@@@:@@@@@@@-@@.......#@*   @@-@-@@@@-..-+#@@@@@@@-@@@@@@@@@@@@@@@@@@
77| @@@@@%@@@@@@%@@.@@@@@@+#@@@@@@=++-@*   @@-%-@%%@@@@@@-@@@@@@@-@@@@@@@@@@@@@@@@@@
78| @@@@@@@@@@@@@@@@+@@@@@+#@@@@@@@-@-@*   @@-@-@.@@@@@@@-@@@@@@=%@@@@@@@@@@@@@@@@@@
79| @@@@@%@@@@@%@@%@@+*@@@+#@@@@@@@-+#@*...@@-+#@@@@@@@@@-@@@@-@@@@@@@@@@@@@@@@@@@@@
80| @@@@@@@@@@@@@@@@@%@@@@#:.@@@@@@.::::++++=:-+++++++++=%@*#@@@@@@@@@@@@@@@@@@@@@@@
81| %@@@@%@@@@@@@@%@@%@%@%%%%%%%%%%%@@@@@@@@@@@@@@@@@@@@@@%@@@@@%@@@@@@@@@@@@@@@@@@@
82| @@@@@@@@@@%%@%%@@%@@%@%@@#:#@@@@@@@@@@@@@@@@@@-@@@@#+@@%@%@@@@@@@@@@@@@@@@@@@@@@
83| @@@@@@@@@@@@@@@@@@@@@@+#@.-@@@@@@@@@+*%@@@@@@@:+%@@@+#@%@@@@@@@@@@@@@@@@@@@@@@@@
84| @@@@@@@@@@@%@@@@@@@@@*+@@:@@@@@@@@@@-@-@@@@@@@..#@@@@-@@@@@%%@@@@@@@@@@@@@@@@@@@
85| @@@@@@@@@@@@@@@@@@@@@*+@%:@@@@@@@@@.@@-@@@@@@@..#@@@@-@@@@@@@@@@@@@@@@@@@@@@@@@@
86| 
87| 
88| ---
89| 
90| ## Hackin' ASCII (agregado)
91| 
92|             .-\"\"\"-.
93|            /  .===.\\
94|           /  / 6 6 \\ \\ 
95|           |  \\ 0 /  | |
96|           |  /`---'\\ | |
97|           /_/  .-.  \\_\\
98|          /`   /   \\   `\\
99|         /    /_____\\    \\
100|        /_.-\"`  | |  `\"-._\\
101|        /`       | |       `\\
102|       /         |_|         \\
103|      /  H A C K I N G   E T H I C A L \\
104|     /_______________________________\\
105| 
106|    /* Stay curious. Learn ethically. Respect systems. */
107| 
108| 
109| ```
```

