# Guia-N-4

-Objetivo  General

•	Analizar el concepto de un fasor y realizar operaciones aritméticas con números complejos, tanto en su forma polar como rectangular.

-Objetivos Especificos

•	Comprender el concepto de que es un fasor para que se utiliza y su uso en el armado de los circuitos 

•	Operar con números complejos y coordenadas, tanto en su forma polar como rectangular y comprobar los resultados con una calculadora

•	Mostrar cuál de las dos alternativas es más factible en la hora de trabajar mejorando asi la comprensión del estudiante al momento de resolver los ejercicios de aplicación 



------Marco Teorico-----

Fasores
(Análisis en circuitos eléctricos)

¿Qué es un Fasor?
Es posible suprimir del problema de cálculo la frecuencia del circuito, simplificando así la ecuación para concentrarse en la obtención de la amplitud y fase de los distintos valores. Es aquí donde se introduce el concepto de Fasor, que tiene como mayor virtud el poder convertir las ecuaciones integro-diferenciales en ecuaciones algebraicas complejas, más sencillas de resolver que aquellas expuestas en los temas anteriores.
Se estudió en las primeras secciones que el voltaje y la corriente pueden ser representados, respectivamente, como sigue:
 
Estas representaciones se caracterizan por mostrar:
 
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
 
Relaciones fasoriales para R, I, C.
Los Fasores se utilizan para representar las corrientes y las tensiones eléctricas, sin embargo, debido a que en los elementos básicos están presentes ambos, es posible establecer la relación que existe entre los Fasores de corriente y tensión en cada elemento.
Véase la deducción de la relación fasorial en la lectura obligatoria, y examine los diagramas fasoriales característicos para cada elemento.
A continuación, se muestran las relaciones fasoriales para resistencias, inductores y capacitores
Resistor	V=RI
Inductor	V=jωlI
Nota: En el inductor, la tensión adelanta a la corriente por 90º.
Capacitor	I=jωCV
Nota: En el capacitor, la corriente adelanta a la tensión por 90º

Para comprender mejor la representación gráfica del adelanto y atraso entre señales, analice la animación siguiente:
 




Impedancia y admitancia 
Cada elemento utilizado en circuitos eléctricos tiene un cociente de tensión-corriente, ya sea este constante o variable con el tiempo. En este curso se examinan únicamente los circuitos lineales invariables con el tiempo, por lo tanto, las relaciones tensión-corriente a estudiar son constantes.
Cuando esta relación se hace entre Fasores de tensión y de corriente, el resultado también tiene forma fasorial, que se puede expresar en forma rectangular o polar, y de aquí nacen las definiciones de impedancia (Z) y admitancia (Y).
Se definirá la impedancia de un elemento como la razón del voltaje del fasor con la corriente de ese mismo fasor, la cual se definirá como Z.
Para establecer una aplicación más física del concepto, la impedancia en circuitos de CA tiene un rol semejante al de la resistencia en circuitos de CD.
Impedancia de un resistor	Z=R
Impedancia de un inductor	Z=jωL
Impedancia de un capacitor 	Z=1/jωC

Se definirá la admitancia como el recíproco de la impedancia, y se indica con la letra Y
Y=1/Z




Análisis de circuitos utilizando Fasores
Las técnicas clásicas de análisis de circuitos en corriente directa se derivan en su totalidad de tres leyes principales: Ley de Ohm, Ley te tensiones de Kirchhoff (LVK) y Ley de corrientes de Kirchhoff (LCK). Si estas leyes son aplicables en circuitos excitados en corriente alterna, las técnicas de análisis utilizadas en circuitos de corriente directa también lo son para estos casos.
Revise la deducción de cómo las leyes básicas de análisis de circuitos aplican para circuitos excitados senoidalmente, lo que da sustento a la aplicación de las técnicas de análisis conocidas. Refiérase a la lectura obligatoria para encontrar las demostraciones de las conclusiones siguientes:
	La ley de voltaje de Kirchhoff (LVK) se mantiene en el dominio de la frecuencia, con voltajes de fasor.
	La ley de la corriente de Kirchhoff (LCK) se mantiene en el dominio de la frecuencia, con corrientes de fasor.
	La división de voltaje y de corriente también es aplicable con Fasores
La división de voltaje y corriente se establecen como se muestra en la figura 








Divisores de corriente y tensión

Para analizar circuitos en el dominio de la frecuencia, se utilizan los mismos procedimientos que se utilizaron al hallar soluciones para circuitos en el dominio del tiempo, utilizando impedancias en lugar de resistencias.
En algunos circuitos conviene hallar la admitancia, pues resulta más sencillo realizar el cálculo de admitancias cuando los elementos de circuito están en paralelo, ya que se realiza una suma algebraica
 (Y_1+Y_2+⋯.+Y_n)
Y no una suma del reciproco
(1/Z_1 +1/Z_2 +⋯+1/Z_n )^(-1)
Sin embargo, debe ser cuidadoso al momento de expresar su respuesta, y no olvidar responder el valor de la variable que se le solicita.














Representacion fasorial 
La corriente alterna se puede representar con una flecha girando a velocidad angular ω. Este elemento recibe el nombre de fasor y se representa como un número complejo.

Su longitud coincide con el valor máximo de la tensión o corriente (según sea la magnitud que se esté representando). También se utiliza el valor RMS en lugar del valor máximo. En ese caso habría que dividir el valor máximo por raíz de 2.

El ángulo (corrimiento de la señal sobre el eje horizontal) representa la fase. La velocidad de giro ω está relacionada con la frecuencia de la señal.


 

En muchas ocasiones, las tensiones y las corrientes de circuitos con corriente alterna presentan desfasajes entre sí (corrimientos horizontales). En los diagramas fasoriales esto se representa con un ángulo entre los Fasores. En el ejemplo siguiente hay dos señales desfasadas 90° y a la izquierda de las mismas se pueden ver los dos Fasores con un ángulo de 90 grados entre sí.


 


En un diagrama fasorial quedarían representadas de la siguiente manera:





Al igual que los números complejos, los Fasores pueden estar representados en forma biónica o polar (también existen otras como la trigonométrica y la exponencial). En algunos casos nos conviene una forma de expresarlos y en otros casos será más simple hacer cuentas con la otra forma.
Forma polar
Los Fasores pueden describirse matemáticamente en forma polar, es decir como un módulo y un ángulo. A continuación vamos a ver un ejemplo de cómo indicar una tensión alterna con un fasor.

Supongamos que tenemos la siguiente expresión de tensión:

 

La expresión anterior se puede representar como un fasor indicando la tensión máxima (15 V en el ejemplo) y el ángulo de desplazamiento (30° en el ejemplo). En forma polar, la tensión anterior queda representada por el siguiente fasor:

 





Gráficamente lo podemos ver de la siguiente forma:

 

Como convención, las señales deben estar expresadas con una función coseno y con un valor positivo para realizar un análisis fasorial. En caso de no estar expresadas de esta manera debemos convertirlas. Esto se explica detalladamente en la próxima sección.

Forma binómica o rectangular 
Otra forma de expresar a un fasor, es la forma binómica, es decir como: a + j b  siendo a la parte real y b la parte imaginaria.

La señal del ejemplo anterior la podemos expresar en base a sus componentes rectangulares como:

 

Gráficamente nos queda el diagrama de la siguiente manera:

 


Conversión de Fasores 
(Coordenadas polares a rectangulares y viceversa de un fasor aplicado en la resolución de ejercicios)
Es posible convertir fácilmente un fasor de la forma polar a la forma binómica y viceversa. Para ello se utilizan los mismos conceptos que para convertir números complejos entre ambas formas de representación.
Las coordenadas polares o sistema de coordenadas polares son un sistema de coordenadas bidimensional en el que cada punto del plano se determina por una distancia y un ángulo. Este sistema es ampliamente utilizado en física y trigonometría.

	Conversión de coordenadas cartesianas a polares
 
 Las coordenadas polares,  , se definen de la siguiente manera:
 La coordenada   es la distancia del punto   al origen. Puede variar entre los valores  .
 
 
La coordenada   es el ángulo que forma el vector   con el eje vertical de las   en sentido horario. Puede variar entre los valores   (en radianes), o   en centígrados.
 
o bien
  
Ejemplos
	 
 


Así, nuestro punto en coordenadas polares es  .
	  

 

Así, nuestro punto en coordenadas polares es  .
 
	 
   
 Así, nuestro punto en coordenadas polares es  .
	Conversión de coordenadas polares a cartesianas
 
 En este caso, dadas la coordenadas polares  , tenemos que las coordenadas cartesianas,  , están dadas por
 
 


Ejemplo. 
Consideremos el punto  



