# Guia-N-4

---------------Fasores---------------

------(Analisis en circuitos electricos)------

1. Objetivos

-Objetivo  General

•	Analizar el concepto de un fasor y realizar operaciones aritméticas con números complejos, tanto en su forma polar como rectangular.

-Objetivos Especificos

•	Comprender el concepto de que es un fasor para que se utiliza y su uso en el armado de los circuitos 

•	Operar con números complejos y coordenadas, tanto en su forma polar como rectangular y comprobar los resultados con una calculadora

•	Mostrar cuál de las dos alternativas es más factible en la hora de trabajar mejorando asi la comprensión del estudiante al momento de resolver los ejercicios de aplicación 


2. Requisitos previos


Investigue: concepto de fasor  tanto en su forma polar como en su forma rectangular  y si respectiva representacion grafica
Investigar: formulas de conversion de coordenadas polares a rectangulares y vicervesa



3. Marco Teorico


Fasores
(Análisis en circuitos eléctricos)

¿Qué es un Fasor?
Es posible suprimir del problema de cálculo la frecuencia del circuito, simplificando así la ecuación para concentrarse en la obtención de la amplitud y fase de los distintos valores. Es aquí donde se introduce el concepto de Fasor, que tiene como mayor virtud el poder convertir las ecuaciones integro-diferenciales en ecuaciones algebraicas complejas, más sencillas de resolver que aquellas expuestas en los temas anteriores.
Se estudió en las primeras secciones que el voltaje y la corriente pueden ser representados, respectivamente, como sigue:

![1](https://user-images.githubusercontent.com/75337022/107398001-32ea7c00-6acd-11eb-9f9e-77addd5da01a.png)
 
Estas representaciones se caracterizan por mostrar:

![2](https://user-images.githubusercontent.com/75337022/107398021-3a118a00-6acd-11eb-8c16-4f92a381fde9.png)

 
Si se trabaja con términos cuya frecuencia no varía, ω se puede suprimir de los cálculos temporalmente.

Para la representación fasorial de las fuentes, se utilizará la amplitud de la tensión o corriente (dependiendo de la cantidad que se desee representar) y también un ángulo, el cual tomará como referencia la función coseno.
Se introduce así el concepto de fasor, el cual es un número complejo que representa la magnitud y la fase de una sinusoide. Es una transformación del dominio del tiempo al dominio de la frecuencia, que contiene información sobre la magnitud y la fase. Con su uso, los cálculos se vuelven más sencillos.
¿Cuándo se representan las cantidades en su forma fasorial?
Se puede usar la representación fasorial cuando:

	El circuito es lineal
	
	Se busca respuesta de estado estable
	
	Todas las fuentes independientes senoidales tienen la misma frecuencia
	
Diagrama Fasorial
Debido a que el fasor se representa como magnitud y fase (magnitud y ángulo), es posible representarlo gráficamente de igual manera que los vectores, aunque estos tengan un significado diferente. Esta representación es conocida como diagrama fasorial, y es muy útil para comprender las relaciones entre diferentes variables eléctricas, facilitando en muchos casos la resolución de problemas de circuitos eléctricos.
La representación de un fasor se muestra a continuación.

![3](https://user-images.githubusercontent.com/75337022/107398048-40076b00-6acd-11eb-8ed7-1496d0b686d1.png)
 
Relaciones fasoriales para R, I, C.
Los Fasores se utilizan para representar las corrientes y las tensiones eléctricas, sin embargo, debido a que en los elementos básicos están presentes ambos, es posible establecer la relación que existe entre los Fasores de corriente y tensión en cada elemento.
Véase la deducción de la relación fasorial en la lectura obligatoria, y examine los diagramas fasoriales característicos para cada elemento.
A continuación, se muestran las relaciones fasoriales para resistencias, inductores y capacitores

![4](https://user-images.githubusercontent.com/75337022/107398070-4695e280-6acd-11eb-86d7-9d80765f41bb.png)

Para comprender mejor la representación gráfica del adelanto y atraso entre señales, analice la animación siguiente:
 
![5](https://user-images.githubusercontent.com/75337022/107398089-4ac20000-6acd-11eb-817f-5a95e78fdcb1.jpg)


Impedancia y admitancia 
Cada elemento utilizado en circuitos eléctricos tiene un cociente de tensión-corriente, ya sea este constante o variable con el tiempo. En este curso se examinan únicamente los circuitos lineales invariables con el tiempo, por lo tanto, las relaciones tensión-corriente a estudiar son constantes.
Cuando esta relación se hace entre Fasores de tensión y de corriente, el resultado también tiene forma fasorial, que se puede expresar en forma rectangular o polar, y de aquí nacen las definiciones de impedancia (Z) y admitancia (Y).
Se definirá la impedancia de un elemento como la razón del voltaje del fasor con la corriente de ese mismo fasor, la cual se definirá como Z.
Para establecer una aplicación más física del concepto, la impedancia en circuitos de CA tiene un rol semejante al de la resistencia en circuitos de CD.

![6](https://user-images.githubusercontent.com/75337022/107398126-51e90e00-6acd-11eb-800f-55d43363f96a.png)

Se definirá la admitancia como el recíproco de la impedancia, y se indica con la letra Y

![7](https://user-images.githubusercontent.com/75337022/107398203-64fbde00-6acd-11eb-943d-0a961b3c96b0.png)


Análisis de circuitos utilizando Fasores
Las técnicas clásicas de análisis de circuitos en corriente directa se derivan en su totalidad de tres leyes principales: Ley de Ohm, Ley te tensiones de Kirchhoff (LVK) y Ley de corrientes de Kirchhoff (LCK). Si estas leyes son aplicables en circuitos excitados en corriente alterna, las técnicas de análisis utilizadas en circuitos de corriente directa también lo son para estos casos.
Revise la deducción de cómo las leyes básicas de análisis de circuitos aplican para circuitos excitados senoidalmente, lo que da sustento a la aplicación de las técnicas de análisis conocidas. Refiérase a la lectura obligatoria para encontrar las demostraciones de las conclusiones siguientes:

	La ley de voltaje de Kirchhoff (LVK) se mantiene en el dominio de la frecuencia, con voltajes de fasor.
	
	La ley de la corriente de Kirchhoff (LCK) se mantiene en el dominio de la frecuencia, con corrientes de fasor.
	
	La división de voltaje y de corriente también es aplicable con Fasores
	
La división de voltaje y corriente se establecen como se muestra en la figura 

![8](https://user-images.githubusercontent.com/75337022/107398230-69c09200-6acd-11eb-8e1c-24921086991b.jpg)


Divisores de corriente y tensión

Para analizar circuitos en el dominio de la frecuencia, se utilizan los mismos procedimientos que se utilizaron al hallar soluciones para circuitos en el dominio del tiempo, utilizando impedancias en lugar de resistencias.
En algunos circuitos conviene hallar la admitancia, pues resulta más sencillo realizar el cálculo de admitancias cuando los elementos de circuito están en paralelo, ya que se realiza una suma algebraica
 
 ![9](https://user-images.githubusercontent.com/75337022/107398251-6e854600-6acd-11eb-9502-18af0ec57ddf.png)
 
Sin embargo, debe ser cuidadoso al momento de expresar su respuesta, y no olvidar responder el valor de la variable que se le solicita.


Representacion fasorial 
La corriente alterna se puede representar con una flecha girando a velocidad angular ω. Este elemento recibe el nombre de fasor y se representa como un número complejo.

Su longitud coincide con el valor máximo de la tensión o corriente (según sea la magnitud que se esté representando). También se utiliza el valor RMS en lugar del valor máximo. En ese caso habría que dividir el valor máximo por raíz de 2.

El ángulo (corrimiento de la señal sobre el eje horizontal) representa la fase. La velocidad de giro ω está relacionada con la frecuencia de la señal.

![11](https://user-images.githubusercontent.com/75337022/107398297-7b099e80-6acd-11eb-8a8b-fb9958aa17e6.jpg)


En muchas ocasiones, las tensiones y las corrientes de circuitos con corriente alterna presentan desfasajes entre sí (corrimientos horizontales). En los diagramas fasoriales esto se representa con un ángulo entre los Fasores. En el ejemplo siguiente hay dos señales desfasadas 90° y a la izquierda de las mismas se pueden ver los dos Fasores con un ángulo de 90 grados entre sí.

![10](https://user-images.githubusercontent.com/75337022/107398276-75ac5400-6acd-11eb-90d5-b1501dc3cd00.jpg)

En un diagrama fasorial quedarían representadas de la siguiente manera:

![12](https://user-images.githubusercontent.com/75337022/107398310-8066e900-6acd-11eb-9dc1-4735d446d7c8.jpg)


Al igual que los números complejos, los Fasores pueden estar representados en forma biónica o polar (también existen otras como la trigonométrica y la exponencial). En algunos casos nos conviene una forma de expresarlos y en otros casos será más simple hacer cuentas con la otra forma.


---Forma polar

Los Fasores pueden describirse matemáticamente en forma polar, es decir como un módulo y un ángulo. A continuación vamos a ver un ejemplo de cómo indicar una tensión alterna con un fasor.

Supongamos que tenemos la siguiente expresión de tensión:

![13](https://user-images.githubusercontent.com/75337022/107398370-8bba1480-6acd-11eb-86d4-5af22540d970.png)

 
La expresión anterior se puede representar como un fasor indicando la tensión máxima (15 V en el ejemplo) y el ángulo de desplazamiento (30° en el ejemplo). En forma polar, la tensión anterior queda representada por el siguiente fasor:

![14](https://user-images.githubusercontent.com/75337022/107398391-91175f00-6acd-11eb-91f4-f3e0f2595543.png)

 
Gráficamente lo podemos ver de la siguiente forma:

![15](https://user-images.githubusercontent.com/75337022/107398404-9674a980-6acd-11eb-8bab-8e3462c3cdca.jpg) 

Como convención, las señales deben estar expresadas con una función coseno y con un valor positivo para realizar un análisis fasorial. En caso de no estar expresadas de esta manera debemos convertirlas. Esto se explica detalladamente en la próxima sección.

---Forma binomica o rectangular 

Otra forma de expresar a un fasor, es la forma binómica, es decir como: a + j b  siendo a la parte real y b la parte imaginaria.

La señal del ejemplo anterior la podemos expresar en base a sus componentes rectangulares como:

![16](https://user-images.githubusercontent.com/75337022/107398434-9bd1f400-6acd-11eb-836e-1df3668bdf5e.png)


Gráficamente nos queda el diagrama de la siguiente manera:

![17](https://user-images.githubusercontent.com/75337022/107398463-a3919880-6acd-11eb-9d20-2d7fd965ea03.jpg)

 
Conversión de Fasores 

(Coordenadas polares a rectangulares y viceversa de un fasor aplicado en la resolución de ejercicios)

Es posible convertir fácilmente un fasor de la forma polar a la forma binómica y viceversa. Para ello se utilizan los mismos conceptos que para convertir números complejos entre ambas formas de representación.
Las coordenadas polares o sistema de coordenadas polares son un sistema de coordenadas bidimensional en el que cada punto del plano se determina por una distancia y un ángulo. Este sistema es ampliamente utilizado en física y trigonometría.


![Conversion 1](https://user-images.githubusercontent.com/75337022/107406008-ee171300-6ad5-11eb-82a1-dbc7e5ad5543.png)

![Conversion 2](https://user-images.githubusercontent.com/75337022/107406023-f3745d80-6ad5-11eb-9ae6-5e43506c8dca.png)

![Conversiones 3](https://user-images.githubusercontent.com/75337022/107406047-f8391180-6ad5-11eb-8832-a599d8157ea1.png)

![Conversion 5](https://user-images.githubusercontent.com/75337022/107406057-fd965c00-6ad5-11eb-84a7-7d27c70ffe78.png)

![Conversion 6](https://user-images.githubusercontent.com/75337022/107406075-02f3a680-6ad6-11eb-8a15-da59bed0afe9.png)

![Antes de las conversiones](https://user-images.githubusercontent.com/75337022/107405992-e9525f00-6ad5-11eb-96fd-aee1ceca8b69.png)

5.1 Resolucion de los problemas

![Anexo 1 Conversion polares a rectangulares_pages-to-jpg-0001](https://user-images.githubusercontent.com/75337022/107407180-5fa39100-6ad7-11eb-8f73-950caf63fff2.jpg)

![Anexo 1 Conversion polares a rectangulares_pages-to-jpg-0002](https://user-images.githubusercontent.com/75337022/107407207-692cf900-6ad7-11eb-9ace-1a66a34cdb03.jpg)

![Anexo 1 Conversion polares a rectangulares_pages-to-jpg-0003](https://user-images.githubusercontent.com/75337022/107407241-70540700-6ad7-11eb-8ae3-f89132bab53e.jpg)

![Anexo 1 Conversion polares a rectangulares_pages-to-jpg-0004](https://user-images.githubusercontent.com/75337022/107407275-777b1500-6ad7-11eb-9f4a-850c0a930c31.jpg)

![Anexo 2 Conversion rectagular a polar_page-0001](https://user-images.githubusercontent.com/75337022/107407326-8792f480-6ad7-11eb-8f3f-ff234a6ecb6d.jpg)

![Anexo 2 Conversion rectagular a polar_page-0002](https://user-images.githubusercontent.com/75337022/107407346-8cf03f00-6ad7-11eb-8f2a-56ea0f7baaee.jpg)

![Anexo 2 Conversion rectagular a polar_page-0003](https://user-images.githubusercontent.com/75337022/107407425-a4c7c300-6ad7-11eb-89e0-3e0ed45b61c9.jpg)

![Anexo 2 Conversion rectagular a polar_page-0004](https://user-images.githubusercontent.com/75337022/107407392-9aa5c480-6ad7-11eb-8089-7826ecdcf4ca.jpg)

![Anexo 3 Ejercicios de conversiones_page-0001](https://user-images.githubusercontent.com/75337022/107407462-ad1ffe00-6ad7-11eb-9eb6-3e3714c4236f.jpg)

![Anexo 3 Ejercicios de conversiones_page-0002](https://user-images.githubusercontent.com/75337022/107407495-b9a45680-6ad7-11eb-884d-a4ab798f476b.jpg)

![Anexo 3 Ejercicios de conversiones_page-0003](https://user-images.githubusercontent.com/75337022/107407515-c032ce00-6ad7-11eb-9795-f41ab3bd12ff.jpg)


6. Conclusiones

•	El uso de los fasores es una herramienta matemática de gran ayuda, pues simplifica el análisis de los circuitos, haciendo más fácil los cálculos, ya que si se toma la señal en el dominio del tiempo se tendría que trabajar con ecuaciones diferenciales, lo cual haría más largo el procedimiento.

•	Los resultados obtenidos a mano fueron cercanos, pero no iguales a los obtenidos en la calculadora en este documento. 

•	La conversión de unidades facilito la resolución de ejercicios


7. Recomendaciones

•	Investigar, proponer y resolver ejercicios de análisis de circuitos que involucren fasores

•	Siempre tratar de manejar en la resolución de ejercicios ya sea todo en coordenadas polares o rectangulares facilitando asi la comprensión del mismo y la fácil resolución de los cálculos

•	Utilizar herramientas como calculadora web o manual para verificar los resultados tomando en cuenta los cálculos hechos a mano para comprobar que las respuestas sean correctas


8. Bibliografia

Dorf, R., Svoboda J. Circuitos Eléctricos, 8va edición, sección 10.8: "Leyes de Kirchhoff que utilizan fasores".
Dorf, R., Svoboda J. Circuitos Eléctricos, 8va edición, sección 10.9: "Análisis del voltaje de nodos y de la corriente de enlaces utilizando fasores".
Dorf, R., Svoboda J. Circuitos Eléctricos, 8va edición, sección 10.6: "Relaciones de fasor para los elementos R, L y C".
Dorf, R., Svoboda J. Circuitos Eléctricos, 8va edición, sección 10.7: "Impedancia y admitancia".
Dorf, R., Svoboda J. Circuitos Eléctricos, 8va edición, sección 10.5: "El Fasor".

2007-2021 FisicaPracticar.com recuperado de: https://www.fisicapractica.com/matematica.php

Superprof, Conversión: Coordenadas cartesianas a polares recuperado de: https://www.superprof.es/apuntes/escolar/matematicas/aritmetica/complejos/coordenadas-cartesianas-a-polares.html





