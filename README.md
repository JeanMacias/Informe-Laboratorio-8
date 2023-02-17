# Informe-Laboratorio-8

**NOMBRES:** JOAN CALDERÓN, JEAN MACIAS

**NRC:** 10063

# **OBJETIVOS**

### **OBJETIVO GENERAL**

Determinar las características y el comportamiento de las ondas sinusoidales mediante la implemtentación del circuito propuesto y el uso de un osciloscopio digital.

### **OBJETIVOS ESPECÍFICOS**

* Determinar el voltaje pico, voltaje pico a pico, voltaje rms de la onda sinusoidal.

* Determinar el periodo, frecuencia y frecuencia angular.

* Aprender a utilizar un osciloscopio de forma correcta.

# **MARCO TEÓRICO**

# **MATERIAL Y EQUIPO REQUERIDO**

![image](https://user-images.githubusercontent.com/116774235/219495305-5eb95d96-df85-4e1a-837d-9f8a29687fec.png)

# **PROCEDIMIENTO**

**8.5.1. Implemente el circuito de la figura 7.1.**

> ***Figura 7.1:***

![image](https://user-images.githubusercontent.com/116774235/219495734-ffc53bff-c383-44b3-8dcb-8211147f6303.png)

> ***Circuito Armado en Proteus:***

![image](https://user-images.githubusercontent.com/116774235/219534068-d6e49a0d-994b-4efc-ac8e-636fb318f95c.png)

**8.5.2. Ajuste el generador de funciones, para que proporcione una señal de 20 Vpp a una frecuencia de 2.5Khz.**

![image](https://user-images.githubusercontent.com/116774235/219666601-e550ab16-cbba-4dd2-a8a2-2ad422bd16c0.png)

Puesto que el valor pico a pico es de 20V, se procede a colocar un valor pico de 10V.

**8.5.3. Conecte el osciloscopio al resistor de carga RL. Observe la señal que aparece en el osciloscopio.**

![image](https://user-images.githubusercontent.com/116774235/219669311-67b10bf1-547b-42fc-b3ec-a3f441f46f04.png)

**8.5.4. Responda las siguientes preguntas:**

> ¿Cuántas divisiones por cuadro abarca la amplitud pico de la señal de salida?

Abarca aproximadamente 6.9 cuadros y cada cuadro equivale a 1V.

> ¿En qué valor está posicionada la perilla VOLTS/DIV?

Está en el valor de 1V.

> ¿Cuántas divisiones por cuadro abarca un ciclo completo de la señal de salida?

Abarca 4 divisiones por cuadro.

**8.5.5. ¿Cuál es la amplitud de voltaje y el periodo de la señal que aparece en la pantalla del osciloscopio?**

* **Amplitud de voltaje:**

![image](https://user-images.githubusercontent.com/116774235/219670961-c8695f29-8f76-45d8-ab45-c9ab64c2af2f.png)

La amplitud de voltaje es igual al valor pico, que en este caso es 6.85V

* **Periodo:**

Sabemos que un ciclo abarca 2 cuadros y cada cuadro equivale a 0.2ms = 0.0002s. Entonces:

(2) * (0.0002) = 0.0004s = 0.4ms

**8.5.6. Determine la frecuencia natural (Hz) y la frecuencia angular (rad/s) de la señal de salida.**

* **Frecuencia:**

Sabemos que: F = 1/T, entonces:

F = 1/(0.0004) = 2500Hz

* **Frecuencia Angular:**

Sabemos que w = 2πF, entonces:

w = 2π(2500)

w = 15707.96 (rad/s)

**8.5.7. Con el multímetro digital mida el voltaje de salida en RL**

![image](https://user-images.githubusercontent.com/116774235/219675539-e9acd576-b2c2-403d-a40e-4e800b164d56.png)

El multímetro representa el valor rms.

**8.5.8. Compare el voltaje medido en el punto 8.5.5. y el obtenido en el punto 8.5.7.**

* **¿Coinciden?**

No coinciden.

* **¿Por qué?**

Porque el valor medido con el osciloscopio solo representa el valor máximo que proporciona la fuente de voltaje alterna, mientras que el multímetro mide el voltaje rms, es decir, mide el valor del voltaje tomando en cuenta la idea de que la fuente fuera continua.

# **CONCLUSIONES**

* Se logró determinar de manera eficaz los valores de los voltajes, frecuencias y periodos. Todo gracias a la ayuda del simulador Proteus.

* El valor de voltaje propocionado por el osciloscopio no es igual al valor de voltaje medido con un multímetro.

# **BIBLIOGRAFÍA**

* FLOYD, THOMAS L.Principios de circuitos eléctricos. Octava edición. PEARSON EDUCACIÓN, México, 2007

* BOYLESTAD, ROBERT L. Introducción al análisis de circuitos. PEARSON EDUCACIÓN, México, 2004
