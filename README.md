# Compañia-de-Seguros

- El algoritmo de k vecinos (kNN) se basa en la idea de que los objetos similares estarán cerca unos de otros en el espacio de características. Siempre hay que tener los valores de las caracteristicas a evaluar, ya que para una clasificación más precisa, es necesario escalar los datos. Y dependiendo del tipo de datos con los que se maneje, es necesario escoger una distancia Manhattan o Euclidiana.

- Cuando hemos trabajamos con matrices hemos vistos que los resultados no siempre serán exactos, ya que no hay un límite en la precisión con la que se realizan los cálculos. Esto es especialmente evidente en operaciones que involucran decimales o números grandes, debido a la forma en que se representan y almacenan los números de manera aproximada.

- A veces necesitamos transformar nuestros datos (características) para que sean más fáciles de manejar por los algoritmos. Si usamos una matriz invertible (es decir, una matriz cuya inversión es posible), podemos transformar las características sin que esto altere la capacidad de los algoritmos para hacer predicciones. La regresión lineal es un buen ejemplo: aunque transformemos los datos con una matriz, los valores que predice el modelo no cambiarán.
