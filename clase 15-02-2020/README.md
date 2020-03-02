# Sistemas lineales y no lineales

* Escalamiento
* Superposición: Suma de espacios lineales
* 

# Introducción al aprendizaje de maquina
* Aprendizaje a partir de datos
* Se estudian diferentes algoritmos que permiten resolver diferentes problemas de predicción
* El algoritmo se diseña con base en un modelo matemático o función, y una base de datos
* Se desea extraer conocimiento a partir de datos


Cuando estrategias de inteligencia artificial tienden a repetirse se le llama **Efecto burbuja** 

# Big data
Desde hace mucho tiempo la humanidad genera miles de millones de datos diariamente. De estos lotes de datos se puede obtener conclusiones predicciones, analsiis entre otros

# Data Scientisc
Persona la cual le da valor a los datos donde de estos llega a conclusiones, predicciones, de lotes de datos.

# En colombia el big data que?
Colombia realiza convocatorias de big data y data analytics

# Nociones basicas
## Nociones básicas 1
* Sean dos variables aleatorias x= {x_1, ..., x_M}
* Discretas: 

* Aleatoriedad: son valores que no se conocen con certeza cuales van a ser

* Se tienen N **realizaciones** o **Objetos muestrales** una relación es la muestra de un conjunto de datos de X y Y

* Se define la **probabilidad conjunta** como:
o(x=x_i, y=y_j)= n_ij/N
Es decir la probabilidad de que dos hechos ocurran al mismo tiempo

donde n_ij se define como el número de realizaciones en las que X= n_ij

## Nociones básicas 2

* Sea c_i el número de relaizaciones en las que X toma el valor x_i (ind, del valor de Y)


* Se define la **probabilidad marginal** de X = x_i, la probabilidad marginal refiere a la probabilidad de una **sola variable** donde se verifican cosas de esa variable como:

p(X=x_i)= c_i/N = 1/N sum (_(j) (n_ij)) = sum(^(L) _(j=1) p(X=x_i, Y=y_i))

## Nociones Básicas 3
* Se define la **probabilidad condicional** de Y= y_j dado X=x_i como
    p(Y=y_j | X= x_i) = n_ij/c_i 

Además,

    p(X=x_i, Y=y_j) = n_ij/N = n_ij/c_i c_i/N
    = p(Y=y_j|X=x_i) p (X=x_i)

* **Regla de la suma:** p(X) = sum()

## Nociones básicas 4:
* Teorema de Bayes:
    p(Y|X) = (p(X|Y) p(Y))/p(X)
(p(X|Y) -> Probabilidad de que sea una fruta 

p(Y|X) -> Probabilidad de que algo Y dado a que X

P(y=algo|x) -> Probabilidad de que y algo dado en X



* Independencia:
    
    p(Y|X) = p(Y), p(X, Y) = p(X) p(Y)
    Si Y y X son independientes entonces la probabilidad de X y de Y es el producto de las **marginales**

## Ejemplo
    P(X|Y=1) es 
    total de casos a que Y es 1 / total de casos de ese Y=1

# Densidad de probabilidad

## Densidad de probabilidad 1
* **función de densidad de probabilidad** p(x) debe cumplir que

p(x) >= 0
integrate ((+infinite),(-infinite), p(x)dx) = 1 -> La suma de todas las probabilkidades debe ser igual a 1

* Para un intervalo
    p(X pertenece (a,b)) = integrate...

* la **función de distribución de probabilidad (distribución acumulativa) se define como

P(X)= integrate((X),(-infinite),())
-> su limite tiende a 1

# Vectores aleatorios
* Supóngase un conjunto de D variables aleatorias X_1, X_, ..., X_D.
* Estas variables aleatorias pueden representarse como un vector columna de dimensiones D \* 1

* Un valor específico de **X** se denota como **x** = (x_1, x_2, ..., X_D)^T

* Los vectores van en **negrilla** y los que son escalares no van en negrilla

# Densidad de probabilidad conjunta
* La densidad de probabilidad conjunta para **X**, p(**x**) = p(x_1, ..., x_D), es decir se aplica en un conjunto.

p(**x**) >= 0
integrate((+infinite),(-infinite),(p(**x**)d**x**)) = 1
* En este caso es una integral que va respecto a todas y cada una de las variables

* **Regla de la suma** obtiene la probabilidad marginal:
    p(**x**) = integrate(p**x**, **y**) d**y**
    de sta manera consume las variables de **y** y quedan las de x

* Regla del producto:
    p(**x**,**y**) = p(**y**|**x**)p(**x**)

* Teorema de bayes

# Valor esperado y covarianza

## Valor esperado y covarianza 1
* El **valor esperado** o la **esperanza** de una función f(x) está definida como:

E\[f\] = sum(_(x), p(x)f(x)), E\[f\] = integrate(p(x)f(x)dx)

si f(x) es x entonces
= integrate(p(x)x dx)
es la media del valor esperado

* la **esperanza muestral de una función f(x) se define como
E\[f\] es aproximadamente 1/N sum(^(N), \_(i=1), f(x\_i))

si f(x) es x entonces

= P / N sum()

* **varianza** se define como que tanto varia el valor de un punto dado, la dispersión que tiene la variable

## Valor esperado y covarianza 2
* La **covarianza** de dos variables aleatorias X y Y se define como:
cov\[x, y\] = E\_x,y \[{x - E\[x\] \]}{y-E\[y\]}\]
    = E\_x,y\[xy\] - E\[x\]E\[y\]

sigma^2 = sum()

* La esperanza de un vector de variables aleatorias **X**, se define como
E\[**x**\]

La covarianza define que tanto varia o la dispersión que hay entre dos variables

* L covarianza para el caso de vectores de variables aleatorias **X** y **Y**, se define como una matriz **simetrica**

cov\[**X**, **Y**\] = E\_x,y\[{**X** - E\[**X**\]}\]
Si una variable no tiene varianza con otra es que son independientes entre si

## Valor esperado 3

## Distribución Gaussiana 1

* Productos internos
* 

