# Informe-01 

TEMA: PRÁCTICA No. 1 LEYES DE KIRCHHOFF

ESTUDIANTES:  MENESES JARRIN SANTIAGO JAVIER OSEJO CUESTA BRANDON DILLAN PEREZ CEDILLO DAMIAN ALEXANDER 
    
DOCENTE: DARWIN OMAR ALULEMA FLORES 
 
NRC:  8703

En esta práctica trataremos el tema de las leyes de Kirchhoff y su funcionamiento sobre un circuito de resistencias mixto. Usando herramientas de simulación digital, definiremos los valores a calcular y las conexiones debidas para cada elemento dentro de la placa de conexión. Usando las definiciones de cada ley de Kirchhoff (voltaje y corriente), demostraremos si el circuito cumple con esta ley en cada tramo y nodo respectiv o

1.- Plantamiento del problema

Vamos a determinar los valores de voltajes y corriente de cada resistencia, los valores de entrada y salida de cada corriente por nodo respectivo, y comprobar que la direccion de las corrientes sean adecuadas tomando en cuenta que en un nodo comun, si una corriente entra, obligatoriamente una debe salir, analizar por tramos los valores de los voltajes considerando como dato importante la ley de ohm para una comprobacion efimera y  sertera de los datos calculados en un circuito ideal de resitencias mixto, utilizando las leyes de Kirchhoff determinaremos si existe un cumplimiento optimo de las deficion de ley de voltajes y de corrientes

2.Objetivo de la practica

Explicar y demostrar experimentalmente la Ley de Kirchhoff de Voltajes y la Ley de Kirchhoff de Corrientes. 

2.1 Objetivos especifivos 

2.1.1- Descubrir los valores de corriente y voltaje en su respectiva resistencia, usando leyes de Kirchhoff en Voltajes y Corrientes

2.1.2- Identificar cuántos tramos o mallas podremos analiza

2.1.3- Determinar cuántos nodos existen dentro del circuitos tomando en cuenta que no se repitan

2.1.4- Usar adecuadamente los elementos de medición para evitar un error en los valores

3.- Marco Teórico

Leyes de Kirchhoff
Las leyes de Kirchhoff son enunciados basados en la conservación de la energía, estas leyes son bastante usadas en la actualidad en varias ingenierías relacionadas con la electrónic, ya que nos permite conocer el valor de corrientes y tensiones de una red de mallas y nodos de una forma bastante sencilla. 

Las leyes de Kirchhoff son dos las cuales dicen: 

Primera Ley de Kirchhoff.- 

La primera Ley de Kirchhoff, o también conocida como ley de corrientes de Kirchhoff o ley de nodos, dice que: “En cualquier nodo, la suma de las corrientes que entran en ese nodo es igual a la suma de la corrientes que salen. De forma equivalente, la suma de todas las corrientes que pasan por el nodo es igual a cero”.
Entonces siguiendo el enunciado obtenemos la siguiente ecuación: 

I1+I2+I3+...+In=0

Segunda Ley de Kirchhoff.- 

La segunda ley de Kirchhoff, también conocida como la Ley de tensiones de Kirchhoff nos dice que: “En un circuito cerrado, la suma de todas las caídas de tensión es igual a la tensión total suministrada. De forma equivalente, la suma algebraica de las diferencias de potencial eléctrico en un circuito es igual a cero.” 
Entonces siguiendo el enunciado obtenemos la siguiente ecuación: 

V1+V2+V3+...+Vn=0

4.- Diagram 

![Ejemplo de circuito resistivo](https://github.com/BrandonOsejo/lab-circuitos/blob/master/L1I1.png)

5.- MATERIAL Y EQUIPO REQUERIDO

![Tabla materiales](https://github.com/BrandonOsejo/lab-circuitos/blob/master/L1I2.png)

6.- PROCEDIMIENTO  
 
6.1. Arme el circuito que se muestra en la figura 1.1. 

![MHE](https://github.com/BrandonOsejo/lab-circuitos/blob/master/L1I3.png)

6.2. Mida el voltaje y corriente en cada uno de los elementos del circuito. Anote los resultados de las mediciones en la tabla 1.1

| variable | valor calculado | valor medio |
|  :---:|  :---: | :---: |
| `VR1(V)` | 2.05[v] |2.05[v]|
| IR1(mA) | 2.05[mA] |2.05[mA]|
| VR2(V)| 4.25[v]|4.25[v]|
| IR2(mA) | 1.089[mA] |1.09[mA]|
| VR3(V) | 2.125[v]|2.12[v]|
| IR3(mA) | 0.9659[mA] |0.965[mA] |
| VR4(V)| 2.125[v] |2.12[v]|
| IR4(mA)| 0.9659[mA] |0.965[ mA]|
| VR5(V) | 3.7[v] |3.7[v]|
| IR5(mA) | 2.05[mA] |2.05[mA]|

Tabla 1.1. Resultados obtenidos de voltaje y corriente, en cada elemento del circuito.

6.3. Verifique si se cumple la Ley de Kirchhoff de Voltajes en cada trayectoria cerrada, considerando las elevaciones de voltaje con signo positivo y las caídas de voltaje con signo negativo. Anote los resultados en la tabla 1.2. 

| Voltaje| Trayectoria 1 | Trayectoria 2 |Trayectoria 3 |
|  :---:|  :---: | :---: | :---: |

|        | Calculado | Medido|Calculado |Medido|Calculado|Medido|
|  :---:|  :---: | :---: | :---: |:---: | :---: | :---: |
| VF(V)       | 10[v]   |10[v]   |  0      |0       |10[v]     |10[v]   |  
| VR1(V)      | -2.05[v]|-2.05[v]|  0      |0       |-2.05[v]  |-2.05[v]|  
| VR2(V)      | -4.25[v]|-4.25[v]|4.25[v]  |4.25[v] | 0        |0       |
| VR3(V)      | 0       |0       |-2.125[v]|-2.12[v]|-2.1249[v]|-2.12[v]| 
| VR4(V)      | 0       |0       |-2.125[v]|-2.12[v]|-2.1249[v]|-2.12[v]|
| `VR5(V)`    | -3.69[v]|-3.7[v] | 0       |0       |-3.69[v]  |-3.7[v] |
| `SUMATORIA V` | 0[v]    |0[v]    | 0[v]    |0[v]    |0[v]      |0[v]    |

6.4. Verifique si se cumple la Ley de Kirchhoff de Corrientes en cada nodo, tomando con signo positivo las corrientes que entran al nodo y con signo negativo las que salen  del nodo. Anote los resultados en la tabla 1.3.

| Corriente| Nodo 1 | Nodo 2 |Nodo 3 |Nodo 4 |Nodo 5 |
|  :---:|  :---: | :---: | :---: | :---: | :---: |

|        | Calculado | Medido|Calculado |Medido|Calculado|Medido|Calculado|Medido|Calculado|Medido|
|  :---:|  :---: | :---: | :---: |:---: | :---: | :---: |:---: |:---: |:---: |:---: |
| IF(mA)        | 2.05 |2.05  |  0    |0     |0      |0    |0     |  0  |-2.05    | -2.05  |     
| IR1(mA)       | -2.05|-2.05 |  2.05 |2.05  |0      |0    |0     |  0  |  0    |  0    |    
| IR2(mA)       | 0    |0     |-1.089 |-1.09 | 0     |0    |1.089 |   1.09    |  0  |  0    |  
| IR3(mA)       | 0    |0     |-0.9659|-0.96 |0.9659 |0.96 |0     | 0    |  0    |  0    |   
| IR4(mA)       | 0    |0     |0      |0     |-0.9659|-0.96|0.9659|   0.96 |   0 |  0    |  
| IR5(mA)       |  0   |0     | 0     |0     |0      |0    |-2.05 |   -2.05|  2.05  | 2.05  |  
| `SUMATORIA I` | 0[mA]|0[mA] | 0[mA] |0[mA] |0[mA]  |0[mA]|0[mA] |  0[mA] | 0[mA]  |0[mA]   |  

6.5  ​Compare los resultados medidos con los valores obtenidos al analizar el circuito analíticamente y concluya al respecto
 
 
7  ​ Explicaciones del codigo Fuente

   Para la implementacion dentro del simulador  para la implemente debemos tomar primero la fuente de voltaje con los datos a proporcionar al circuito correctos, tomar el protoboar y realizar una conexión directa con los polos negativos y positivos de la fuente de poder, realizar un puente de un extremo del protoboarda al otro para asegurar que la corriente  pase por todos los tramos de la plataforma y poder utilizar mas espacio de trabajo, tener en cuenta que cada nodo de conexíon dentro del protoboard, se representa como una linea vertical de espacios para poder conectar los elementos en el nodo respectivo. El circuito requiere un  voltaje de entrada de 10v asi que en la fuente se colocaran los 10v de entrada y ya colocados los elementos cerrando el circuito, se procede a iniciar la simulación
