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

[Ver Diagramas de fujo](https://github.com/TomasCobos-rgb/INFORME-2-LAB-SE-ALES-/blob/main/PARTE%20A.2/Diagramas%20de%20flujo/.md#diagramas-de-flujo)

[Ver Parte Python](https://github.com/TomasCobos-rgb/INFORME-2-LAB-SE-ALES-/blob/main/PARTE%20A.2/.md#parte-python)


### PARTE B
Se definieron las siguientes señales: 

```python
x1[nTs]=cos⁡(2π100nTs))   para 0 ≤n< 9
x2[nTs]=sin⁡(2π100nTs)     para 0 ≤n< 9 
para Ts=1.25 ms
```
El objetivo de esta parte B es encontrar la correlación cruzada entre ambas señales, la representación gráfica y describir la secuencia resultante y finalmente responder ¿En qué situaciones resulta útil aplicar la correlación cruzada en el procesamiento digital de señales?

[Desarrollo Parte B](https://github.com/TomasCobos-rgb/INFORME-2-LAB-SE-ALES-/blob/main/PARTE%20B/.md)

### PARTE C
En este apartado se presenta el proceso completo de análisis de una señal biológica generada con un generador de señales. Aquí se podrá observar:

1. Determinación de la frecuencia de Nyquist de la señal inicial.
2. Digitalización de la señal, empleando una frecuencia de muestreo cuatro veces mayor que la de Nyquist.
3. Caracterización en el dominio temporal, calculando media, mediana, desviación estándar, máximo y mínimo, además de la clasificación de la señal según sus propiedades.
4. Análisis en el dominio de la frecuencia mediante la Transformada de Fourier, mostrando:
   
   4.1. Espectro de la señal.
   4.2. Densidad espectral de potencia.
   4.3. Estadísticos en frecuencia (frecuencia media, mediana y desviación estándar).
   4.4. Histograma de frecuencias.

