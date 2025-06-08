Tema 4: Análisis de problemas y toma de decisiones
================================================================

La modelización
---------------

***Modelo.*** Representación simplificada de una parte de la realidad. El principal objetivo de un modelo es permitir una mejor comprensión y descripción de la parte de la realidad que representa. Se pueden clasificar considerando diversos criterios:

1. **Modelos objetivos y subjetivos.** Cuando en la toma de decisiones interviene sucesos no experimentables objetivamente, y no existen métodos formales, los modelos han de ser:
    - Informales
    - Subjetivos
    - Basarse en la intuición
2. **Modelos analíticos y de simulación.** Los modelos analíticos sirven para obtener soluciones.

    - Permiten obtener información sobre los efectos de las posibles decisiones, pero luego el decisor ha de elegir la alternativa que le resulte más conveniente. En este sentido, pueden ser prescriptivos o descriptivos.

    Entre estos modelos se encuentran:

    - **Modelos de optimización**. Permiten determinar los valores que ha de darse a las variables de modo que se maximice o minimice otra variable que se tiene como objetivo. Son **prescriptivos**.
    - **Modelos de simulación**. Representaciones simplificadas Re la realidad sobre las que se opera para estudiar los efectos de distintas alternativas de actuación. Son **descriptivos**.

3. **Modelos estáticos y dinámicos:**
    - Estáticos. Aquellos que no utilizan la variable tiempo. 
    - Dinámicos. Incorporan como variable o parámetro fundamental.

4. **Modelos deterministas y probabilísticos:**

    - Deterministas. Los datos se suponen conocidos con certeza.
    - Probabilísticos, aleatorios o estocásticos. Uno o varios datos solo se conocen en términos de probabilidades.

Ambientes de decisión
---------------------

El nivel de información determina el tipo de ambiente de la decisión. Se distinguen los siguientes **ambientes de decisión**:

- **Certeza.** El decisor conoce con absoluta seguridad los estados de la naturaleza que van a presentarse.
- **Riesgo.** El decisor no sabe qué estados de la naturaleza se presentarán, pero sí cuales pueden presentarse y la probabilidad que tiene cada uno de ellos.
- **Incertidumbre estructurada.** Se conocen los estados de la naturaleza, pero no la probabilidad de cada uno de ellos.
- **Incertidumbre no estructurada.** Es aquél en el que ni siquiera se conocen los posibles estados de la naturaleza.

Para pasar de un tipo de ambiente a otro es necesario obtener un cierto grado de información: cuando mayor se la información, menor será la incertidumbre.

***Proceso de aprendizaje.*** Según la teoría de la decisión, es el proceso de consecución de información que (en algún caso) permite pasar de un ambiente a otro.

Criterios de decisión en ambiente de incertidumbre
--------------------------------------------------

En un entorno de escasez de información como es el de incertidumbre, ha de intervenir en gran medida la subjetividad:

- Si la incertidumbre no está estructurada, ni se puede obtener más información, la decisión deberá basarse en la intuición.
- Si la incertidumbre está estructurada, la decisión continúa incorporando una carga de subjetividad muy elevada.

Los principales **criterios de decisión** en un entorno de incertidumbre estructurada son los siguientes:

1. **Criterio de Laplace, racionalista o de igual verosimilitud**. Parte del postulado de Bayes: si no se conocen las probabilidades asociadas a cada uno de los estados de la naturaleza no hay razón para pensar que uno tenga más probabilidades que otros.

Se calcula la media aritmética de los resultados que se pueden derivar de cada una de las decisiones y, dependiendo de los resultados: 

- Favorables. Se elije el resultado medio más elevado.
- Desfavorables. Se elige el resultado medio más bajo.

2. **Criterio optimista.** Criterio que seguiría una persona que pensara que, para cualquier estrategia elegida, el estado presentado sería el más favorable para ella:

    - Resultados favorables \(\rightarrow\) **criterio maxi-max**. Se determina cuál es el resultado más elevado que puede alcanzarse con cada estrategia y, posteriormente, se elige aquella a la que le corresponda el máximo entre esos máximos.
    - Resultados desfavorables \(\rightarrow\) **criterio mini-min**. Se determina cuál es el mejor resultado que puede obtenerse con cada estrategia (el menor) y se elige aquella a la que le corresponda el mínimo entre esos mínimos.

3. **Criterio pesimista o de Wald.** Seguido por una persona que piense que para cualquier estrategia elegida, el estado presentado es el menos favorable para ella.

4. **Criterio de optimismo parcial de Hurwicz.** Compromiso entre los criterios optimista y pesimista mediante un **coeficiente de optimismo** ($\alpha$); comprendido entre $0$ y $1$, y de su complemento a la unidad; que es el denominado **coeficiente de pesimismo** ($1 - \alpha$).

    - El mejor de los resultados de cada estrategia se pondera con el coeficiente de optimismo, en tanto que el peor de los resultados se pondera con el de pesimismo.

5. **Criterio del mínimo pesar o de Savage.** Es seguido por los que tienen aversión a arrepentirse por equivocarse. Formalmente, ha de partiste de la elaboración de la denominada **matriz de pesares**. El pesar es lo que se deja de ganar por no elegir correctamente.

Una estrategia $A$ está **dominada** por otra estrategia $B$, si cualquiera que sea el estado de la naturaleza que se presente, $B$ es igual o mejor que $A$.

La teoría de los juegos de estrategia
-------------------------------------

En los **juegos de estrategia** el resultado final depende de las decisiones tomadas por los diversos jugadores. Se pueden clasificar de acuerdo con diversos criterios:

1. Según el **número de participantes** en los juegos.
2. Según se la **ganancia total obtenida por el conjunto de todos los participantes**. Cuando el total de lo que unos ganan coincide con el total de lo que otros pierden, el saldo total es cero, o de suma nula.
    - Los juegos de suma no nula pueden ser de suma constante o de suma variable, según sea constante o variable ese saldo neto total.
3. Según el **número de jugadas** que comprenden.
4. Según sea la **información de la que disponen los participantes** en el momento de jugar. Los juegos pueden ser de información completa y de información incompleta.
5. Finalmente, según los **elementos que intervengan en las decisiones**, se distingue:

- **Juegos de estrategia pura**. En las decisiones de los jugadores solo interviene su actuación.
- **Juegos de estrategia mixta**. Interviene algún elemento aleatorio introducido por los propios jugadores.

**Juego rectangular**. Para obtener una solución de un juego rectangular tendremos que hallar las mejores estrategias de los jugadores y el **valor del juego**, es decir, la cantidad que gana un jugador y que el otro la pierde.

**Juegos con punto de silla**. Juegos en los que el maxi-min del ganador coincide con el mini-max del perdedor. 

- La técnica para encontrar un punto de silla es determinar un número que sea el menor de su fila y el mayor de su columna (supuesto que las columnas se correspondan con las posibles decisiones del perdedor y las filas con las del ganador). Puede haber uno, ninguno o varios puntos de silla.

Probabilidad y riesgo
---------------------

***Probabilidad de Laplace.*** Si de un total de $n$ casos, todos igualmente factibles, un suceso $S$ puede presentarse en $h$ de los casos, la probabilidad de ocurrencia de ese suceso, $P(S)$, es el cociente entre el número de casos favorables y el de casos posibles:

$$P\left( S \right) = \frac{h}{n}$$

***Probabilidad estimada o empírica.*** Según la concepción frecuencial u objetivista de la probabilidad, se tomaría la frecuencia relativa de la aparición del suceso, considerando que el número de observaciones del experimento es suficientemente grande. La probabilidad, en sí, es el límite de la frecuencia relativa cuando el número de observaciones crece indefinidamente.

***Suceso compuesto.*** suceso en el que acontecen dos sucesos $S$ y $T$:

$$P\left( S \cap T \right) = P\left( T \right) \cdot P\left( S \middle| T \right) = P\left( S \right) \cdot P(T|S)$$

***Probabilidad condicionada,*** $P(S|T)$***.*** Es la probabilidad que tiene $S$ sabiendo que ocurrió $T$. Si $S$ y $T$ son sucesos independientes:

$$P\left( S \middle| T \right) = P(S)$$

$$P\left( T \middle| S \right) = P(S)$$

***Sucesos excluyentes.*** Son aquellos sucesos que no pueden presentarse conjuntamente.

***Variable aleatoria.*** Es aquella variable de la que no se sabe con certeza el valor que tomará, sino que sólo se conoce qué valores puede tomar y que probabilidades tiene cada uno de ellos.

***Distribución de probabilidad.*** Conjunto de valores que puede tomar una variable aleatoria y sus respectivas probabilidades. Se suele representar por medio de un **histograma**, es decir, mediante rectángulos cuyas áreas son proporcionales a los tamaños de las probabilidades que representan.

***Esperanza matemática, valor esperado o media.*** Es la media aritmética ponderada de los valores que puede tomar la variable, utilizándose como coeficiente de ponderación de cada valor su probabilidad. Es un valor de referencia que señala donde se encuentra centrada la distribución de probabilidad.

$$E\left( x \right) = x_{1} \cdot p_{1} + x_{2} \cdot p_{2} + \ldots + x_{n} \cdot p_{n} = \overline{x}$$

***Varianza.*** Es la esperanza matemática de los cuadrados de las desviaciones de los valores probables respecto a su media. Da idea de la forma de la distribución de probabilidad. La unidad de medida de la varianza es el cuadrado de la unidad de medida de la variable de que se trate.

$$\sigma^{2}\left( x \right) = \left( x_{1} - \overline{x} \right)^{2} \cdot p_{1} + \left( x_{2} - \overline{x} \right)^{2} \cdot p_{2} + \ldots + \left( x_{n} - \overline{x} \right)^{2} \cdot p_{n}$$

***Desviación típica.*** Es la raíz cuadrada positiva de la varianza. Se mide en las mismas unidades que la variable en cuestión.

$$\sigma\left( x \right) = \sqrt{\sigma^{2}(x)}$$

Cuando la desviación típica es muy pequeña, puede decirse que hay una probabilidad elevada de que la variable tome un valor muy próximo a su valor esperado. Si es muy elevada, habrá una gran probabilidad de que la variable se desvíe, al alza o a la baja, respecto a ese valor medio. En el caso de certeza, la dispersión vale cero y va creciendo a medida que el riesgo va siendo mayor.

Si hay varias alternativas, a cada una de las cuales le corresponde un valor esperado diferente y un nivel de riesgo distinto, la decisión dependerá de la subjetividad del decisor, es decir, de su nivel de **aversión al riesgo**. Los decisores que tienen gran aversión al riesgo precisan un gran beneficio esperado para asumir niveles de riesgo relativamente pequeños; por el contrario, aquellos que tienen poca aversión al riesgo están dispuestos a arriesgarse a cambio de beneficios esperados moderados.

***Coeficiente de variación.*** Es un parámetro que combina el riesgo y la esperanza matemática.

$$\text{CV}\left( x \right) = \frac{\sigma\left( x \right)}{E\left( x \right)}$$

El análisis bayesiano
---------------------

***Teorema de Bayes.*** Permite modificar las probabilidades de los distintos estados, o sucesos aleatorios, en función de la información adicional de la que va disponiéndose, es decir, permite modificar las probabilidades a media que se avanza en el proceso de aprendizaje.

$$P\left( S_{i} \middle| T \right) = \frac{P\left( S_{i} \right) \cdot P(T|S_{i})}{P\left( T \middle| S_{1} \right) \cdot P\left( S_{1} \right) + P\left( T \middle| S_{2} \right)P\left( S_{2} \right) + \ldots + P\left( T \middle| S_{n} \right) \cdot P(S_{n})}$$

La determinación del grado de confianza
---------------------------------------

***Variable discreta.*** El número de valores que puede tomar la variable es finito.

***Variable continua.*** La variable aleatoria puede tomar un número infinito de valores. Uno de los tipos de variables continuas más importante es el integrado por las denominadas **variables normales**, a cuyas distribuciones de probabilidad se les denomina también **distribuciones normales**.

![Resultado de imagen de distribucion normal](./media/media/image4.png)

Figura . Distribución normal

Características de las distribuciones normales:

- Son simétricas y tienen una forma acampanada, por lo que a su representación se le denomina **campana de Gauss**.
- La probabilidad de que la variable tome un valor en concreto es igual a cero.
- La probabilidad de que la variable tome un valor comprendido en un cierto intervalo finito es una cantidad finita e igual al área existente bajo la campana en ese intervalo. El área total que hay bajo la campana vale $1$.
- La esperanza matemática de la variable se encuentra en el centro de la distribución y, dado que ésta es simétrica y que su área total es igual a $1$, tanto el área situada a la izquierda de su valor esperado, como la existente a su derecha, han de valer $0,5$.
- Esta distribución queda descrita conociendo su esperanza matemática y de su varianza: la esperanza matemática determina el lugar en el que se encuentra centrada la distribución, y la varianza determina su forma.

La siguiente expresión significa que la variable $x$ sigue una distribución normal con una esperanza matemática igual a $E(x)$ y una desviación típica igual a $\sigma(x)$:

$$x \rightarrow N\left\lbrack E\left( x \right),\ \sigma(x) \right\rbrack$$

***Teorema fundamental del límite.*** Si una variable está formada por la suma de un infinito número de variables independientes entre sí, cada una de las cuales tiene una distribución de media y varianza finitas, esa variable seguirá una distribución normal. En rigor, el teorema solo se cumple cuando el número de variables que se suman es infinito, pero se pueden considerar aplicable de forma aproximada cuando dicho número es suficientemente grande y la aproximación tenderá a ser mejor cuanto mayor sea ese número.

Cuando una variable, $x$, está formada por la suma de otras variables, su esperanza es igual a la suma de las esperanzas de estas variables:

$$E\left( x \right) = E\left( x_{1} \right) + E\left( x_{2} \right) + \ldots + E(x_{n})$$

Además, si estas variables son independientes entre sí, la varianza de la variable-suma es la suma de las varianzas:

$$\sigma^{2}\left( x \right) = \sigma^{2}\left( x_{1} \right) + \sigma^{2}\left( x_{2} \right) + \ldots + \sigma^{2}\left( x_{n} \right)$$

***Distribución normal estandarizada o tipificada.*** Es aquella cuya esperanza matemática vale cero y cuya desviación típica es igual a uno. Se denomina $\xi$ a la variable que tiene esta distribución:

$$\xi \rightarrow N(0,1)$$

Si la variable $x$ sigue una distribución normal, entonces la variable tipificada será:

$$\xi = \frac{x - E\left( x \right)}{\sigma(x)}$$

A este proceso de disponer la variable $x$ en número de desviaciones típicas respecto a su media, se le denomina **tipificación**. Tipificando la variable, es posible calcular cualquier probabilidad relativa a la misma.

La teoría de la información
---------------------------

***Teoría de la información.*** Desarrollada por Shannon, ofrece un enfoque para medir la información. La información proporcionada por la materialización de un suceso depende de la probabilidad de su acaecimiento; proporciona tanta más información cuanto mayor sea la sorpresa que produce, es decir, cuanto menor fuera la probabilidad de su acaecimiento.

Se denomina $h(P)$ a la información proporcionada por la realización de un suceso de probabilidad $P$. Para determinar la forma concreta de esta función, se debe tener en cuenta que:

1. Debe ser decreciente con $P$, pues la información aumenta al reducirse la probabilidad del suceso.

2. La función ha de tender a infinito cuando la probabilidad $P$ tienda a cero.

3. La materialización de un suceso seguro no proporciona información alguna, por lo que la función debe tomar el valor cero cuando $P$ sea igual a uno.

4. A cada uno de los infinitos posibles valores de $P$ les debe corresponder una única medida de información.

5. La información proporcionada por la ocurrencia conjunta de dos o más sucesos independientes entre sí debe ser igual a la suma de las informaciones que proporcionan los distintos sucesos en su acontecer.

$$h\left( P \right) = \log\left( \frac{1}{p} \right) = - log(P)$$

$$h\left( P \right) = \log_{2}\left( \frac{1}{p} \right) = - \log_{2}\left( P \right)\ \lbrack bits\rbrack$$

$$h\left( P \right) = \ln\left( \frac{1}{p} \right) = - \ln\left( P \right)\left\lbrack \text{nits} \right\rbrack$$

El logaritmo puede ser neperiano (en cuyo caso la información viene medida en **nits**), decimal (la unidad será el **hartley**) o binario (la información se mide en **bits**). Por comodidad se suele usar la base binaria:

$$h\left( P \right) = - \log_{2}\left( P \right)$$

Si se considera un conjunto de sucesos complementarios y mutuamente excluyentes entre sí, la información esperada será:

$$H = - \left\lbrack P_{1} \cdot \log\left( P_{1} \right) + P_{2} \cdot \log\left( P_{2} \right) + \ldots + P_{n} \cdot \log\left( P_{n} \right) \right\rbrack$$

***Entropía.*** Mide la incertidumbre que afecta al sistema antes de saber cuál de los sucesos va a producirse. Es siempre positiva. La entropía es máxima cuando todos los sucesos tienen la misma probabilidad de presentarse.

Se considera una comunicación o noticia, denominada mensaje, que, con su acaecimiento, hace variar la probabilidad de un suceso, $j$, desde $P_{j}$ hasta $Q_{j}$, modificando, con ello, la incertidumbre. Dicha variación de incertidumbre, es decir, la modificación de la información que se derivaría de la ocurrencia de $j$, valdrá:

$$h\left( P_{j} \right) - h\left( Q_{j} \right) = - \log\left( P_{j} \right) + \log\left( Q_{j} \right) = \log\left( \frac{Q_{j}}{P_{j}} \right)$$

Esta variación representa el **contenido informativo del mensaje** o la ganancia de información derivada del mismo.

Si se trata de un conjunto de sucesos, se define, de manera semejante,
el contenido informativo esperado del mensaje como:

$$I\left( Q:P \right) = Q_{1}\log\left( \frac{Q_{1}}{P_{1}} \right) + Q_{2}\log\left( \frac{Q_{2}}{P_{2}} \right) + \ldots + Q_{n}\log\left( \frac{Q_{n}}{P_{n}} \right)$$

$I\left( Q:P \right)$ es la **información de canal** y, siempre es no negativa. Alcanza su valor mínimo solo cuando el mensaje no modifica la incertidumbre existente, y aumenta de valor a medida que son mayores las variaciones que experimentan las probabilidades de los diversos sucesos.

Si el mensaje hiciera que algún suceso del sistema alcanzara una probabilidad igual a la unidad y, por tanto, que tal probabilidad resultara nula para todos los demás sucesos del mismo, se obtendría:

$$I\left( Q:P \right) = \log\left( \frac{1}{P_{j}} \right) = h(P_{j})$$
