<h1 align='center'>VIDA EN VERDE 🚗🚦</h1><BR>
<h2>MODELO DE DETECCION DE ESTADO DE SEMAFOROS PARA AYUDAR A PERSONAS INVIDENTES</h2>
<div align="center">
  <img alt="Modelo de deteccion de estado de semaforos para ayudar a personas invidentes" src="https://img.freepik.com/vector-gratis/pavimentacion-cruce-peatonal-ciego_1284-22012.jpg?w=826&t=st=1689445322~exp=1689445922~hmac=c85d1279e4b197ee560be7630b381300f7044a5e8d4f2f5f2b263ff943b73ed3" width="500" />
</div>
<br>
<h2>PLANTEAMIENTO DEL PROBLEMA</h2>
<br>
<p>El problema de autonomia con el que cuentan muchas personas invidentes al momento de estar fuera de sus casas es que se les hace dificil movilizarse por las calles de manera autonoma debido p que los conductores no son concientes y en los pasos de sebra no suelen ceder el paso a las personas invidentes al igual que es muy complicado saber el estado de los semaforos para pasar con mas seguridad, debido a la poca inclusion que hay para estos casos no se cuentan con ayudas o sistemas especializados que permitan mejorar estos casos en pro de mejorar estas situaciones</p>

<h2>OBJETIVOS</h2>
<h3>OBJETIVO GENERAL</h3><br>
<p>El objetivo general del proyecto es mejorar la autonomía y seguridad de las personas invidentes al cruzar las calles, mediante el desarrollo de un sistema de IA basado en modelos de aprendizaje que detecten el estado de los semáforos y proporcione indicaciones precisas.</p>

<h3>OBJETIVOS ESPECIFICOS</h3>

<ul>
  <li>Recopilar y etiquetar un conjunto de datos diverso y representativo de imágenes de semáforos peatonales en diferentes condiciones de iluminación y ángulos de visión.</li><br>
  <li>Entrenar y comparar varios modelos supervisados y no supervisados, para determinar cual es el más efectivo en el reconocimiento del estado de los semáforos.</li><br>
</ul>

<h3>DATASET</h3>
<p>Peatones-Traffic-Lights (PTL) es un conjunto de datos de imágenes de alta calidad de intersecciones de calles, creado para la detección de semáforos para peatones y pasos de cebra. Las imágenes tienen variaciones en el clima, la posición y la orientación en relación con el semáforo</p>
<p>las imagenes se encuantran divididas, el dataset origianl con las imagenes a maxima resolución y las recortadas que son las que se utilizaron</p>

<p>
  Original
  <a href='https://dl.orangedox.com/KrVSsK' >Parte 1</a>,
  <a href='https://dl.orangedox.com/CMjgtX'>parte 2</a>.<br>
  Recortado
  <a href='https://drive.google.com/drive/folders/1qmkmT19F9kIjHz9BfVIA1UfixMP2YzqZ?usp=drive_link' >aquí</a>
</p>

<h3>MODELOS PROBADS</h3>

<ul>
  <li>GAUSSIAN NAIVE BAYES:</li><br>
  <p>Es una técnica de clasificación utilizada en Machine Learning (ML) basada en el enfoque probabilístico y la distribución gaussiana. Gaussian Naive Bayes asume   que cada parámetro (también llamado características o predictores) tiene una capacidad independiente de predecir la variable de salida. La combinación de la        predicción para todos los parámetros es la predicción final, que devuelve una probabilidad de que la variable dependiente se clasifique en cada grupo. La           clasificación final se asigna al grupo con mayor probabilidad</p>
  <p>Accuracy:  0.58</p>
  <img alt="Modelo de deteccion de estado de semaforos para ayudar a personas invidentes" src="https://github.com/cesenro2801/PROYECTO_IA/blob/main/IMG/GNB.jpeg" width="500" /><br><br>

  <li>RANDOM FOREST CLASSIFIER:</li><br>
  <p>es uno de los algoritmos más populares y comúnmente utilizados por los científicos de datos. Random forest es un  algoritmo de aprendizaje automático       
  supervisado   que se  usa ampliamente en problemas de clasificación y regresión . Construye árboles de decisión en diferentes muestras y toma su voto mayoritario 
  para la clasificación y el promedio en caso de regresión. Random forest es un algoritmo versátil de aprendizaje automático desarrollado por Leo Breiman y Adele 
  Cutler. Aprovecha un conjunto de múltiples árboles de decisión para generar predicciones o clasificaciones. Al combinar los resultados de estos árboles, el 
  algoritmo de bosque aleatorio ofrece un resultado consolidado y más preciso.</p>
  <p>Accuracy:  0.66</p>
  <img alt="Modelo de deteccion de estado de semaforos para ayudar a personas invidentes" src="https://github.com/cesenro2801/PROYECTO_IA/blob/main/IMG/RFC.jpeg" width="500" /><br><br>

  <li>SUPPORT VECTOR MACHINE:</li><br>
  <p>El objetivo del algoritmo de la máquina de vectores de soporte es encontrar un hiperplano en un espacio N-dimensional (N: el número de características) que      clasifique claramente los puntos de datos. Para separar las dos clases de puntos de datos, se pueden elegir muchos hiperplanos posibles. Nuestro objetivo es        encontrar un plano que tenga el margen máximo, es decir, la distancia máxima entre puntos de datos de ambas clases. Maximizar la distancia del margen proporciona   cierto refuerzo para que los puntos de datos futuros se puedan clasificar con más confianza.</p>
  <p>Accuracy:  0.64</p>
  <img alt="Modelo de deteccion de estado de semaforos para ayudar a personas invidentes" src="https://github.com/cesenro2801/PROYECTO_IA/blob/main/IMG/SVC.jpeg" width="500" /><br><br>

  <li>REDES NEURONALES</li><br>
  <p>es un método de la inteligencia artificial que enseña a las computadoras a procesar datos de una manera que está inspirada en la forma en que lo hace el         cerebro humano. Se trata de un tipo de proceso de machine learning llamado aprendizaje profundo, que utiliza los nodos o las neuronas interconectados en una        estructura de capas que se parece al cerebro humano. Crea un sistema adaptable que las computadoras utilizan para aprender de sus errores y mejorar                 continuamente. De esta forma, las redes neuronales artificiales intentan resolver problemas complicados, como la realización de resúmenes de documentos o el        reconocimiento de rostros, con mayor precisión.</p>
  <p>Accuracy:  0.95652 </p>
  <img alt="Modelo de deteccion de estado de semaforos para ayudar a personas invidentes" src="https://github.com/cesenro2801/PROYECTO_IA/blob/main/IMG/CNN.jpg" width="500" /><br><br>
  
</ul>


<h3>CONCLUSIONES</h3>




