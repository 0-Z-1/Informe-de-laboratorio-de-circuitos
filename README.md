# Informe-de-laboratorio-de-circuitos
Trabajo grupal sobre la primera practica de laboratorio 

### PRACTICA No.1   LEYES DE KIRCHHOFF

#### OBJETIVO GENERAL
- Realizar un circuito con la finalidad de analizar las corrientes y tensiones en cualquier punto de un circuito eléctrico.

#### OBJETIVO ESPECIFICO
-	Determinar el funcionamiento de un sistema de circuitos a través de un simulador Tinkercad que nos va a indicar en diseño 3D.

-	Determinar a través de un suministro de energía los valores de intensidad, voltaje y resistencia del circuito.

-	Conocer la ley de Kirchhoff mediante procesos prácticos utilizando un multímetro para las mediciones de corrientes, resistencias y tenciones en los circuitos, a través de un protoboard , todo esto de manera simulada.


#### MARCO TEORICO

![image](https://user-images.githubusercontent.com/76060654/102250184-3ac4e000-3ed1-11eb-9607-c4ceb64a12c1.png)

#### DIAGRAMA

![image](https://user-images.githubusercontent.com/76060654/102250321-6e076f00-3ed1-11eb-8590-7924c663e3d1.png)

#### LISTA DE COMPONENTES

![image](https://user-images.githubusercontent.com/76060654/102250414-8aa3a700-3ed1-11eb-9880-b1398c08a5c3.png)

#### Explicación

Primero se busca y coloca el protoboar en nuestra simulación, colocado el protoboar buscamos el suministro de energía e indicamos cada cable con su respectiva fase del protoboard para que las conexiones sean útiles (color rojo positivo y color negro negativo), teniendo las resistencias una de 220Ω y la otra 100KΩ la colocamos de forma vertical y horizontal respectivamente y agregamos un cable fuente para conectarlas, obtenemos 2 multímetros para conectarlos en nuestro protoboard uno en el extremo derecho del protoboard y el otro arriba de nuestro suministro de energía; cada multímetro ira conectado a su respectiva resistencia sin olvidar que cada cable se conecta con su fase indicada (“n-n” “p-p”)

En lado positivo de nuestro protoboar conectamos un cable rojo y lo colocamos en el extremo del cable rojo de nuestro multímetro que está arriba de nuestro suministro de energía, y hacemos lo mismo con el otro multímetro, pero con la fase negativa.
Hecho esto nos dirigimos a cambiar el voltaje de nuestro suministro de energía y lo colocamos en “10V” y podrecemos a iniciar el simulador y obtener los resultados del circuito.

#### DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

Las aplicaciones secundarias necesarias para la realización del proyecto tenemos simuladores que de igual forma nos permite realizar las practicas de los laboratorios en Fundamentos de Circuitos:

-	Simulador de construcción de circuitos digitales: Es un programa para construir circuitos digitales sobre un módulo digital virtual a partir de modelos lógicos de circuitos integrados estándares y de aplicación específica. 

-	Powersim: Es un programa que nos permite simular sistemas de control de potencia complejos.

-	Simulador De Circuito On Líne: Se trata de una aplicación software que permite diseñar sistemas de lógica en modo digital, y que proporciona algunos objetos de lógica de bajo nivel y a nivel de registro de funciones. La interfaz del programa es simple y fácil de usar. 

Para que pueda funcionar nuestro proyecto, tenemos que utilizar correctamente los instrumentos de medición, para evitar daños del circuito como también de los materiales.
Conocer el funcionamiento de cada uno de los componentes, en este caso del Protoboard, Multímetro, Resistencias, Suministro de energía.

#### APORTACIONES

Gustav Robert Kirchhoff Fue un científico alemán, cuyas principales contribuciones científicas se centraron en los campos de los circuitos eléctricos.

Descubrió las leyes Generales que rigen con el comportamiento de un circuito eléctrico. Se dedicó al estudio de la termodinámica y realizó investigaciones sobre la conducción del calor.

Es responsable de dos conjuntos de leyes fundamentales, en la teoría clásica de circuitos eléctricos y en la emisión térmica, ambos reciben el nombre de su autor, aunque las más conocidas son referidas a la ingeniería eléctrica.

El científico elaboró un conjunto de leyes para describir cómo se comporta la emisión de luz por objetos incandescentes:

 1. Un objeto sólido caliente produce luz en un espectro continuo.

 2. Un gas tenue produce luz con líneas espectrales en longitudes de onda discretas que dependen de la composición química del gas.

 3. Un objeto sólido a alta temperatura rodeado de un gas tenue a temperaturas inferiores produce luz en un espectro continuo con huecos en longitudes de onda discretas cuyas posiciones dependen de la composición química del gas.

Estas leyes se convirtieron pronto en herramientas fundamentales para el análisis de los circuitos.

-  Primera Ley de Kirchhoff o Ley correspondiente a los nodos: “En cualquier nodo, la suma algebraica de las corrientes eléctricas que entran es igual a la suma de corrientes que salen. Como equivalente, la suma algebraica de todas las corrientes que pasan por el nodo es igual a cero”

-  Segunda Ley de Kirchhoff o Ley correspondiente a las mallas: “en un circuito cerrado de una red, la suma del conjunto de las caídas de tensión en sus componentes es igual al sumatorio de las tensiones suministradas y, por tanto, el sumatorio algebraico de las diferencias de potencial en una malla es cero.”

#### Calculos

##### Calcular la corriente de las mallas

![image](https://user-images.githubusercontent.com/76060654/102919578-1c259280-4457-11eb-8c25-b135d3ba09c8.png)

##### Calcular el Voltaje 

![image](https://user-images.githubusercontent.com/76060654/102919618-2a73ae80-4457-11eb-8230-a1cd3bead4c8.png)

##### Calcular la corriente 

![image](https://user-images.githubusercontent.com/76060654/102919645-38293400-4457-11eb-8ada-aff98d080d14.png)

#### Tablas
#### Tabla 1.1. Resultados obtenidos de voltaje y corriente, en cada elemento del circuito.
| VARIABLE | VALOR CALCULADO | VALOR MEDIO |
| --- | :---: | :---: |
|Vr1 (V) | 2.05	|2.05|
|Ir1 (mA) | 2.59	|2.59|
|Vr2 (V) | 4.24	|4.25|
|Ir2 (mA) | 3.55	|3.57|
|Vr3 (V) | 2.15	|2.12|
|Ir3 (mA) | 1.51	|1.52|
|Vr4 (V) | 2.15	|2.12|
|Ir4 (mA) | 1.51	|1.52|
|Vr5 (V) | 3.69	|3.7|
|Ir5 (mA) | 3.26	|3.26|


#### Tabla 1.2. Verificación de la LVK.
| |Trayectoria 1	|	Trayectoria 2|		Trayectoria 3|	
| --- | :---: | :---: | :---: |
|VOLTAJE|	Calculado\| Medido|	Calculado\|	Medido|	Calculado\|	Medido|
|Vt(V) |	10.00\|10.00|	10.00\|	10.00|0\|   0|
|Vr1 (V) |	2.05\|	2.05|	0\|	0	|0\|	0|
|Vr2 (V) |	4.26\|	4.25|	4.26\|	4.25	|0\|	0|
|Vr3 (V) |	0\|	0|	2.15\|	2.12\|	|0\|	0|
|Vr4 (V) |	0\|	0	|2.15\|	2.12\|	|0\|	0|
|Vr5 (V) |	3.69\|	3.7	| 0\|	0	|0\|	0|
|∑V|	20.01\|	20|	18.56\|	18.49	|0\|	0|


#### Tabla 1.3. Verificación de la LCK.
|	|Nodo 1|		Nodo 2	|	Nodo 3	|	Nodo4|		Nodo5|	
|---|:---:|:---:|:---:|:---:|:---:|
|CORRIENTE|	Calculado\|	Medido	|Calculado	Medido|	Calculado\|	Medido|	Calculado\|	Medido|	Calculado\|	Medido|
|It(mA)|	2.05\|	2.05|	0\|	0|	0\|	0|	0\|	0|	0\|	0|
|Ir1(mA)|	0\|	0|	2.05\|	2.05|	0\|	0|	0\|	0|	0\|	0|
|Ir2(mA)|	0\|	0|	1.066\|	1.09|	0\|	0|	1.06\|	1.09|	0\|0|	
|Ir3(mA)|	0\|	0|	0.94\|	0.95|	0.94\|	0.96|	0\|	0|	0\|	0|
|Ir4(mA)|	0\|	0|	0\|	0	|0.94\|	0.96|	0.94\|	0.96|	0\|	0|
|Ir5(mA)|	0\|	0|	0\|	0|	0\|	0|	0\|	0|	2.06\|	2.05|
|∑I|	2.05\|	2.05	|4.056\|	4.09|	3.88\|	1.92|	2\|	2.05|	2.06\|	2.05|

##### PORCENTAJE DE ERROR

![image](https://user-images.githubusercontent.com/76060654/102919265-8a1d8a00-4456-11eb-9ef4-a0f3b16aeee2.png)

|Resistencias|	Medido(V)|	Calculado(V)|	Medido(I)|	Calculado(I)|	%Error(V)|	%Error(I)|
|---|:---:|:---:|:---:|:---:|:---:|:---:|
|𝑅_1=1𝐾Ω	|2.05	|2.05	|2,59	|2,59	|0|	0|
|𝑅_2=3.9𝐾Ω|	4.24|	4,25|	3.55|	3.57|	0.235|	0.560|
|𝑅_3=2.2𝐾Ω|	2.15|	2.12|	1.51|	1.52|	-1.415|	0.657|
|𝑅_4=2.2𝐾Ω|	2.15|	2.12|	1.51|	1.52|	-1.415|	0.657|
|𝑅_5=1.8𝐾Ω|	3.69|	3.70|	3.26|	3.26|	0.270|	0|


#### Conclusiones

-	Para poder proceder a realizar la práctica de laboratorio de circuitos, se necesitó previamente una introducción a los materiales sin obviar la necesidad de un conocimiento previo acerca de la maquinaria y elementos usados, como la práctica se realizó en un simulador vía web no hubo problema acerca de errores técnicos, pero no elimino el requisito de tener bases acerca de nuestro proyecto.

-	Gracias a dicha práctica ya mencionada se reforzó el conocimiento sobre todo aquel material usado para la misma, ya que se auxilió en cada uno de los elementos utilizados y en cada acción realizada por el ingeniero a cargo. 

-	La práctica realizada con relación a la aplicación de las leyes de Kirchhoff nos dio resultados prácticos y sobre todo educativos en el tema, aunque no tuvimos una hoja de cálculo o cálculos realizados por nosotros mismo antes de completar el simulador los resultados fueron óptimos y esperados por cada uno de los presentes.

-	En la práctica realizada se tuvo el cuidado de no colocar cada aparato y material en una posición incorrecta y distinguir cada cable negativo y positivo con los lados n. y p. de cada material usado, sin llegar a quemar cualquier objeto (resistencia) usado.

#### Bibliografía

Colaboradores de Wikipedia. (2020, 22 septiembre). Gustav Kirchhoff. Wikipedia, la enciclopedia libre. https://es.wikipedia.org/wiki/Gustav_Kirchhoff

EcuRed. (2010). Leyes de Kirchhoff - EcuRed. https://www.ecured.cu/Leyes_de_Kirchhoff

A. (2020, 10 noviembre). Leyes de Kirchhoff. Electronica Completa. https://electronicacompleta.com/leyes-de-kirchhoff/

D., & D. (2020). doalulema/Informe. GitHub. https://github.com/doalulema/Informe/blob/master/README.md

Tinkercad. From mind to design in minutes. (2010). Tinkercad. https://www.tinkercad.com/dashboard?type=circuits&collection=designs

Simulador de circuitos lógicos electrónicos.(2015).CEDAR http://www3.gobiernodecanarias.org/medusa/ecoescuela/recursosdigitales/2015/02/10/simulador-de-circuitos-logicos-electronicos-cedar/#:~:text=Se%20trata%20de%20una%20aplicaci%C3%B3n,simple%20y%20f%C3%A1cil%20de%20usar.

State of the Art Analysis & Modeling Technologies http://www.sdw-latam.com/powersim.html#:~:text=Powersim%20AS%20es%20una%20compa%C3%B1%C3%ADa%20noruega%2C%20establecida%20en%20Bergen.&text=Powersim%20Software%20tiene%20diferentes%20tipos,%E2%80%9Cwhat%20if%E2%80%9D%20en%20profundidad.

#### Anexos

![image](https://user-images.githubusercontent.com/76060654/102250479-a0b16780-3ed1-11eb-953a-62cf21e4652b.png)

**Video**

https://youtu.be/rudD_YaO8do
