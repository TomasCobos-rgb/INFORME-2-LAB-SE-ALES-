### INFORME DE LABORATORIO #2.
Convolución, correlación y transformada de Fourie
---------------
### OBJETIVOS
1. Comprender la convolución y su aplicación en sistemas discretos.
2. Evaluar la correlación como medida de similitud entre señales.
3. Implementar convolución y correlación manualmente y con Python.
4. Generar, muestrear y digitalizar señales biológicas.
5. Caracterizar señales en el dominio del tiempo mediante parámetros estadísticos.
6. Aplicar la Transformada de Fourier para el análisis en frecuencia.
7. Integrar los resultados obtenidos en tiempo y frecuencia para su interpretación.

### PARTE A
Se trabaja con un sistema h[n] definido por los dígitos del código personal y una señal de entrada x[n] definida por los dígitos de la cédula del estudiante. El objetivo es calcular la señal resultante y[n] tanto de forma manual (mediante sumatorias y gráficas) como utilizando Python, con el fin de comparar ambos métodos y reforzar la comprensión del concepto.

### PROCEDIMIENTO 
La primera mitad de la parte A se desarolló manualmente, encontrando la señal y[n] resultante de la convolución y así mismo se realizó su gráfica. 

[Ver Parte Manual](https://github.com/TomasCobos-rgb/INFORME-2-LAB-SE-ALES-/blob/main/PARTE%20A.1/DESARROLLO%20A.1/.md)

Para la segunda mitad de la parte A se utilizó python, nuevamente encontrando la señal y[n] resultante de la convolución y realizando su representación gráfica.

[Ver Parte Python](https://github.com/TomasCobos-rgb/INFORME-2-LAB-SE-ALES-/blob/main/PARTE%20A.2/.md#parte-python)


### PARTE B
Se definieron las siguientes señales: 

```python
x1[nTs]=cos⁡(2π100nTs))   para 0 ≤n< 9
x2[nTs]=sin⁡(2π100nTs)     para 0 ≤n< 9 
para Ts=1.25 ms
```
El objetivo de esta parte B es encontrar la correlación cruzada entre ambas señales, la representación gráfica y describir la secuencia resultante.
3.	Responda ¿En qué situaciones resulta útil aplicar la correlación cruzada en el procesamiento digital de señales?


