# Laboratorio_1

__1. Objetivos__

Objetivos Generales 
* Explicar y demostrar experimentalmente la Ley de Kirchhoff de Voltajes y la Ley de
Kirchhoff de Corrientes.

Objetivos Específicos 
* Calcular mediante una simulación la intensidad y el voltaje que circulan por un circuito Resistivo Mixto.
* Comparar los resultados medidos con los obtenidos analíticamente al estudiar el circuito.
* Identificar los diferentes elementos que se utilizan en la construcción de un circuito eléctrico.
* Verificar si se cumple la ley de Kirchhoff de voltajes en cada trayectoria cerrada.


__2. Marco Teórico__ 

![](https://github.com/ItzAdoc/Laboratorio_1/blob/main/Marco%20Teorico.PNG)


__3. Explicación del Procedimiento__

1.5.1 Arme el cirucito que se muestra en la figura 1.1

![](https://github.com/ItzAdoc/Laboratorio_1/blob/main/Figura%201.1.PNG)

Circuito Armado:

![](https://github.com/ItzAdoc/Laboratorio_1/blob/main/Circuito%20Armado.jpg)

**1.5.2. Mida el voltaje y corriente en cada uno de los elementos del circuito.**

Reducimos el circuito para facilitarnos la medición del voltaje y la corriente de las resistencias, entonces:

![](https://github.com/ItzAdoc/Laboratorio_1/blob/main/Tramo%201.PNG)

La resistencia R3 Y R4 están en serie: 
2,2KΩ + 2,2kΩ= 4,4kΩ
y 4,4kΩ está en paralelo con 3,9kΩ:

![](https://github.com/ItzAdoc/Laboratorio_1/blob/main/1.PNG)

Aplicamos la ley de tensiones de Kirchhoff, con la cual podremos despear la corriente que pasa por el circuito reducido.
+10+V1+V2+V3=0
+10+1ki+2,06ki+1,8ki=0
10+4860i=0

![](https://github.com/ItzAdoc/Laboratorio_1/blob/main/2.PNG)

Una vez obtenido la corriente podemos aplicar la ley de ohm para conseguir el voltaje de cada resistencia del circuito reducido.
V=I*R
V (R1) =2m (1kΩ) = 2V
V (R2) =2m (2,06kΩ) = 4,12V
V (R5) =2m (1,8kΩ) = 3,6V


Ya conociendo la corriente que circula por el circuito reducido, tenemos que volver a extender el circuito y aplicar la ley de división de corriente. Ya que  para obtener el voltaje que circula por las resistencias 3y4 tenemos que saber la corriente que pasan por las resistencias.

![](https://github.com/ItzAdoc/Laboratorio_1/blob/main/3.PNG)

Y una vez obtenido la corriente que pasa por las resistencias 3 y 4 ya podemos aplicar la ley de ohm para conseguir el voltaje de las resistencias.
V (R3) =339μ A (2,2kΩ) = 2,06V
V (R4) =930μ A (2,2kΩ) = 2,06V

Tabla 1.1. Resultados obtenidos de voltaje y corriente, en cada elemento del circuito.

![](https://github.com/ItzAdoc/Laboratorio_1/blob/main/Tabla1.1..PNG)

**1.5.3. Verifique si se cumple la Ley de Kirchhoff de Voltajes en cada trayectoria cerrada,
considerando las elevaciones de voltaje con signo positivo y las caídas de voltaje con
signo negativo. Anote los resultados en la tabla 1.2.**

Tabla 1.2. Verificación de la LVK.

__4. Respuesta a Interrogantes y Calculo de Error__








__5. Video__

https://youtu.be/EOSmhBWmZGU


__6. Coclusiones__ 
* Finalmente la simulación fue exitosa no presentamos ningún problema para obtener las medidas.
* En relación a lo expuesto se pude comprobar que los resultados analíticos son iguales que a los obtenidos en la medición. 


__7. Bibliografía__

* Robbins, A. H. (2008). Análisis de Circuitos Teoría y Práctica. Santa Fe-México: Cengage Learning. 
* Mantilla Quijano, G., & González, H. (1977). La segunda ley de Kirchhoff.
* *Las leyes de Kirchhoff (artículo). (s. f.).* Khan Academy. Recuperado 2 de junio de 2021, de https://es.khanacademy.org/science/physics/circuits-topic/circuits-resistance/a/ee-kirchhoffs-laws
