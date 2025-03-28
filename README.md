# Metodo-Montecarlo
Se emplea el algoritmo de Metrópolis para calcular el comportamiento de fotos al interacuar con un átomo y una cadena de tres átomos
# ¿Qué hace el proyecto?
Implementa el algoritmo de Metrópolis para evaluar la emisión fotoeléctrica en distintos metales al ser iluminados por fotones con diversas energías, esto, definiendo un rango de frecuencias determinado. Se tomaron las funciones de trabajo de cinco metales: aluminio, cobre, oro, plata y hiero para realizas las simulaciones. El código considera el caso en el que se tiene un solo átomo de un metal y otro en el que se tiene una cadena 1D compuesta por tres átomos, para cada uno de los metales considerados.
Para la implementación del código, se define la distribución de energías de los fotones incidentes teniendo en cuenta que la energía de dichos fotones es
$E = hν$. 

Por otra parte, dado que los electrones siguen la distribución de Fermi-Dirac, la probabilidad de encontrar un electrón con energía $E$ está dada por:
$f(E)=\frac{1}{e^{(E-E_F)/k_{B}T}+1}$ ,
donde $E_F$ es la energía de Fermi y $T$ es la temperatura.

Luego, para determinar la emisión de un electrón, se considera la función de trabajo $\phi$ de cada material. De este modo, los valores reportados en la literatura son empleados para determinar el valor de $\phi$ en cada caso. Teniendo en cuenta lo anterior, un electrón solo puede ser emitido si: $E_{fotón}+E_{electrón}>\phi$
# ¿Por qué el proyecto es útil?
Permite comparar las interacciones de los fotones con átomos inviduales frente a una estructura más compleja como una cadena de átomos, incluso se puede escalar para simular redes más cercanas a la realidad variando las propiedades electrónicas de los materiales (como la energía de Fermi, la función de trabajo y la estructura de los electrones), los cuales afectan la emisión fotoeléctrica. Esto es de gran utilidad para el estudio y posterior optimización de dispositivos que dependen de la interacción fotón-electrón, como las celdas solares o dispositivos de detección de radiación.
# ¿Cómo pueden comenzar los usuarios con el proyecto?
1. Defina las constantes involucradas en el proceso de fotoemisión, como por ejemplo, la constante de Planck y la velocidad de la luz.
2. Asegúrese de utilizar las unidades adecuadas y consistentes a lo largo de todo el cálculo para obtener resultados precisos.
3. Fije la temperatura del sistema y la energía de Fermi según su propósito.
4. Defina el número de iteraciones que quiere sean ejecutadas.
5. Definia el rango de energía de los fotones incidentes y la cantidad de fotones que interactuarán con el/los átomo/s.
6. Ejecute el código.
# ¿Dónde pueden recibir ayuda los usuarios con tu proyecto?
Si requiere ayuda con el proyecto o tiene dudas al respecto, escribiar al e-mail: ana.ruizn@udea.edu.co
# ¿Quién mantiene y contribuye con el proyecto?
Ana Luz Ruiz Noriega
