
# Semana 1
## Unidad 1: Lógica
  - Concepto de enunciado
  - Operadores lógicos
  - Tablas de verdad
  - Equivalencias lógicas
  
El estudiante debería ser capaz de interpretar enunciados de primer orden, evaluar valor de verdad de alguna enunciado (sin atómicos), construir tablas de verdad de oraciones con todos sus símbolos atómicos, determinar equivalencia de enunciados usando tablas de verdad.
  
# Semana 2
  - Leyes de equivalencia (leyes lógicas)
  - Inferencia
  - Reglas de inferencia en enunciados de primer orden
  - Demostraciones lógicas
   
El estudiante debe simplificar enunciados usando las leyes de equivalencia y las reglas de sustitución, debe entender el concepto de inferencia lógica, así como realizar inferencias tanto usando la tabla de verdad como usando las reglas de inferencia.
   
# Semana 3
  - Predicados y cuantificadores
  - Inferencia con enunciados cuantificados
  - Por aquí debería estar el **primer examen**
## Unidad 2: Teoría ingenua de conjuntos
  - La noción de conjunto, y la forma exhaustiva y compacta de expresar un conjunto.
  - Subconjuntos e igualdad.
   
El estudiante debe poder entender (¿hacer?) inferencias sobre enunciados cuantificados. Debe ser capaz de determinar si un objeto es un elemento de un conjunto, y entender las nociones de subconjunto e igualdad

# Semana 4
  - Las operaciones conjuntistas de primer orden unarias y binarias: negación, unión, intersección, diferencia, diferencia simétrica. Su relación con operadores lógicos.
  - Ejemplos de demostraciones de igualdad y contención de conjuntos.
    

El estudiante puede determinar si dos conjuntos relación de subconjunto y de igualdad. Debe realizar operaciones conjuntistas, relacionarlas con el álgebra de enunciados (o predicados según sea el caso), y entender y producir demostraciones abstractas. 

# Semana 5
  - El conjunto potencia
  - El producto cartesiano
  - Operaciones indexadas
  - **Segundo examen**
  
El estudiante entiende y puede evaluar el conjunto potencia, producto y realizada operaciones indexadas finitas^[Incluir infinitas si y sólo si las usan en expresiones regulares en matemáticas computacionales]; además puede pensar el producto como conjuntos de puntos en el plano.

# Semana 6
## Unidad 3: Funciones
  - Relaciones y ejemplos
  - La definición de función
    - Como *diagrama de flechas*
    - Como subconjunto de un plano
  - Restrucción y extensión de funciones
  - Imágen de una función (no imagen de un conjunto)
  - Inyectividad y sobreyectividad

El estudiante entiende el concepto de función y reconoce sus partes; y posee herramientas para visualizarlas. Puede determinar (incluso demostrar en ciertos casos) si una función es inyectiva/sobreyectiva.

# Semana 7
  - Composición
  - Inversa y su existencia
  - Imagen y preimágenes de conjuntos bajo funciones
  - **Tercer examen** por aquí
  
El estudiante entiende la estructura algebraica de la composición de funciones^[Implícitamente lo mismo para la inversa], reconoce y usa sus propiedades y teoremas. Puede evaluar imágenes y preimágenes.

# Semana 8
## Unidad 4: Recursión e inducción
  - El principio del buen orden
  - Evaluación de funciones/sucesiones recursivas
  - Exposición de recursividad resolviendo problemas^[ej. Torres de Hanoi, encontrar máximos, ordenar sucesiones, exponenciación, factorial, sumas $\sum_{i<n}a_i$, etc.]
  - Relaciones recursivas bien y mal fundadas.
  - El método de inducción: la forma débil^[$\left(P(0)\wedge \forall n P(n) => P(n+1)\right) \implies \forall n P(n)$] MUCHOS EJEMPLOS
  
El estudiante puede determinar si una relación recursiva está bien fundada, y en tal caso puede evaluar dicha función. El estudiante comprende la necesidad del buen orden para la recursión; además tiene un panorama general de cómo se usa la recursión como herramienta para resolver problemas^[Aquí aún no esperaría que el estudiante pueda hacer recursión todavía.].

# Semana 9
  - Inducción sobre sucesiones recursivas
  - Inducción fuerte^[$\forall n \left(\forall k < n P(k) \implies P(n) \right) \implies \forall n P(n)$]

El estudiante puede usar el principio de inducción para hacer demostraciones acerca de sucesiones definidas mediante el teorema débil de recursión. En particular puede hacer recursión sobre sumas.
  
# Semana 10
  - Divisibilidad
  - Inducción sobre predicados sobre divisibilidad
  - El algoritmo de la división
  - Máximo común divisor
  
El estudiante entiende el concepto de divisibilidad, y es capaz de hacer demostraciones de divisibilidad basadas en inducción. El estudiante entiende el algoritmo de la división; también puede evaluar el máximo común divisor de algunos enteros usando la definición.
  
# Semana 11
  - Combinaciones lineales en los enteros
  - El algoritmo de Euclides
  - Ecuaciones diofantinas lineales
  - Cambios de base numérica
  - **Examen de recursión**
  
El estudiante puede usar el algorimo de Euclides para encontrar el máximo común divisor de manera eficiente; puede usar este mismo algoritmo para determinar, y en tal caso encontrar, soluciones a ecuaciones diofantinas lineales. El estudiante también entiende el concepto de representación numérica relativo a una base, y puede usar el algoritmo de la división para efectuar cambios de base.

# Semana 12
## Combinatoria enumerativa
  - Cardinalidad de un conjunto finito
  - Principio de la suma
  - Principio de inclusión y exclusión (para 2 y 3 uniendos)
  - Diagrama de Venn para realizar conteos
  - Principio del producto
  - Conteo de funciones
  - Conteo del conjunto potencia
  
El estudiante entiende la noción de cardinalidad de un conjunto; reconoce las técnicas básicas de conteo (principio de la suma y del producto) y hace uso de ellos para contar objetos en contexto. Además reconoce la similitud entre una *elección* y una función.
  
# Semana 13
  - Conteo con restricciones
  - La función factorial
  - La función **permutaciones** $P^n_k$
  - Conteo de funciones inyectivas
  - La función **combinaciones** $C^n_k$
  - Conteo de subconjuntos de cardinalidad dada $[A]^n$

El estudiante puede realizar conteo restringido^[sobre el dominio, si/no repeticiones, etc]. Puede también usar el modelo de conteo de combinaciones, y le es clara su diferencia con el modelo de permutaciones. El estudiante entiende por qué las fórmulas de combinaciones y permutaciones.

# Semana 14
  - El teorema del binomio
  - Conteo de configuraciones
  - Coeficiente multinomial
  - El teorema del trinomio y generalizaciones
  
El estudiante puede usar el teorema del binomio (y generalizaciones) para extraer coeficientes de potencias de polinomios. El estudiante reconoce patrones de configuración y los usa como técnica de conteo.

# Semana 15
  - Estrategia de los separadores
  - Conteo recursivo
  - **Examen de conteo**
  
El estudiante realizar conteo de asignación ayudándose del modelo de separadores. También puede realizar conteos de objetos construyendo relaciones recursivas sobre ellos.
