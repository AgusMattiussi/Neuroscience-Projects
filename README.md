# Neurociencia Computacional

Repositorio utilizado para los trabajos prácticos de la materia "16.82 - Neurociencia Computacional".

## TP1 - [Reducción de Dimensionalidad](https://github.com/AgusMattiussi/Neuroscience-Projects/tree/master/TP1)

Trabajo práctico orientativo sobre la reducción de dimensionalidad. El mismo consiste en primero analizar datos de trenes de disparo de neuronas, junto con la velocidad del estímulo recibido en cada momento. Luego para la segunda parte, se trabajo con un dataset de alta dimensión y se aplicaron métodos como PCA, t-SNE y FAMD para reducir los datos a 2 o 3 dimensiones y visualizarlos.


## TP2 - [Análisis de la Actividad Neuronal de un Mono](https://github.com/AgusMattiussi/Neuroscience-Projects/tree/master/TP2)

El proyecto consiste en utilizar datos de actividad neuronal de un mono realizando una tarea de alcance retrasado(*delayed reach task*) para predecir la dirección del movimiento del brazo. Se analiza la influencia de la duración y posición de la ventana de planificación en la precisión del clasificador, así como el impacto de la cantidad de neuronas utilizadas en la decodificación y la cantidad de datos de entrenamiento en la precisión del decodificador. Además, se evalúa cómo varía el rendimiento utilizando diferentes conjuntos de neuronas y tamaños de datos de entrenamiento.

## TP3 - [Red Recurrente Lineal y Sistemas No Lineales](https://github.com/AgusMattiussi/Neuroscience-Projects/tree/master/TP3)

Este trabajo práctico explora la dinámica de redes neuronales recurrentes y sistemas no lineales. En el primer ejercicio, se analiza una red neuronal lineal con dos neuronas (excitatoria e inhibitoria), determinando su matriz de pesos, autovalores y dinámica a través de simulaciones en tiempo continuo y discreto, incluyendo la influencia del ruido. En el segundo ejercicio, se investiga un sistema "Winner-Take-All", calculando puntos fijos y simulando trayectorias desde distintos puntos iniciales, comparando la dinámica linealizada con la no lineal. Estos ejercicios permiten profundizar en la comprensión de la dinámica neuronal mediante métodos analíticos y de simulación.

## TP4 - [Modelos de Neuronas](https://github.com/AgusMattiussi/Neuroscience-Projects/tree/master/TP3)

En este trabajo práctico se analizan diversos modelos de neuronas y sinapsis, incluyendo Poisson, Hodgkin & Huxley, Leaky Integrate and Fire, Tsodyks & Markram, y McCulloch y Pitts. En el primer ejercicio, se elige y justifica el modelo más adecuado para varias investigaciones, como estudiar la forma del potencial de acción con un fármaco, simular fenómenos poblacionales con más de 10 millones de neuronas, estudiar la sincronización de spikes en redes pequeñas, generar datos sintéticos con neuronas ruidosas, y analizar la depresión a corto plazo en neuronas retinales. En el segundo ejercicio, se comparan dos de estos modelos con uno no visto en clase, describiendo sus características, ventajas, desventajas, y aplicaciones, así como su alineación con los niveles de análisis de Marr y los objetivos de Kording et al 2020.