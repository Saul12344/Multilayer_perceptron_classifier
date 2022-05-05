<p align="center">
    <img alt="Logo" src="https://www.tijuana.tecnm.mx/wp-content/uploads/2021/08/liston-de-logos-oficiales-educacion-tecnm-FEB-2021.jpg" width=850 height=250>
</p>
<H2><p align="center">Unit#2 Multilayer perceptron classifier.</p></H2>
<H2><p align="Center">STUDENT'S NAMES: </p></H2>

<H2><p align="Center">López Higuera Saúl Alfredo #18210493</p></H2>

<H2><p align="Center">Ramos Rivera Manuel Isaí #17212931</p></H2>

<H2><p align="center">Multilayer perceptron classifier.</p></H2>
El clasificador de perceptrón multicapa (MLPC) es un clasificador basado en la red neuronal artificial de alimentación. El MLPC consta de múltiples capas de nodos. Cada capa está totalmente conectada a la siguiente capa de la red. Los nodos de la capa de entrada representan los datos de entrada.

 Todos los demás nodos asignan las entradas a las salidas mediante una combinación lineal de las entradas con los pesos del nodo w y el sesgo b y aplicando una función de activación. Esto puede escribirse en forma de matriz para la MLPC con K+1 capas como sigue:
 <br>
 ![logo](/images/1.png)  
 <br>
 Los nodos en las capas intermedias utilizan la función sigmoidea (logística):
 <br>
 ![logo](/images/2.png) 
 <br>
 Los nodos de la capa de salida utilizan la función softmax:
 <br>
 ![logo](/images/3.png) 
 <br>
 ### Ejemplo de multilayer perceptron:
 <br>
 ![logo](/images/4.png) 
 
  <br>
 ###  Multilayer perceptron classifier 
  <br>
  El número de nodos N en la capa de salida corresponde al número de clases.
MLPC emplea retropropagación para aprender el modelo. Utilizamos la función de pérdida logística para la optimización y L-BFGS como rutina de optimización.
<br>
Red Neuronal Artificial de tipo perceptrón simple con n neuronas de entrada, m neuronas en su capa oculta y una neurona de salida.

### Las capas pueden clasificarse en tres tipos:

Capa de entrada: Constituida por aquellas neuronas que introducen los patrones de entrada en la red. En estas neuronas no se produce procesamiento.
Capas ocultas: Formada por aquellas neuronas cuyas entradas provienen de capas anteriores y cuyas salidas pasan a neuronas de capas posteriores.
Capa de salida: Neuronas cuyos valores de salida se corresponden con las salidas de toda la red.
<br>

  ![logo](/images/5.png) 
<br></br>
### Aplicaciones.

<br>
El perceptrón multicapa (de aquí en adelante MLP, MultiLayer Perceptron) se utiliza para resolver problemas de asociación de patrones, segmentación de imágenes, compresión de datos, etc.
<br></br>

### Referencias.

<br>


https://spark.apache.org/docs/2.4.7/ml-classification-regression.html#multilayer-perceptron-classifier
<br>
https://www.youtube.com/watch?v=pbQtQ2Bdzf8
<br>
https://www.youtube.com/watch?v=4Zm5wFfBGvU 
<br>





