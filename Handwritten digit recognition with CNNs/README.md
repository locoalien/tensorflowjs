# 1. Introducción
En este tutorial, crearemos un modelo de TensorFlow.js para reconocer dígitos escritos a mano con una red neuronal convolucional. Primero, entrenaremos al clasificador haciéndole "mirar" miles de imágenes de dígitos escritos a mano y sus etiquetas. Luego, evaluaremos la precisión del clasificador utilizando datos de prueba que el modelo nunca ha visto.

Esta tarea se considera una tarea de clasificación, ya que estamos entrenando al modelo para asignar una categoría (el dígito que aparece en la imagen) a la imagen de entrada. Entrenaremos el modelo mostrándole muchos ejemplos de entradas junto con la salida correcta. Esto se conoce como aprendizaje supervisado.

Que vas a construir
Creará una página web que use TensorFlow.js para entrenar un modelo en el navegador. Dada una imagen en blanco y negro de un tamaño particular, clasificará qué dígito aparece en la imagen. Los pasos involucrados son:

Cargue los datos.
Definir la arquitectura del modelo.
Entrene al modelo y controle su rendimiento mientras entrena.
Evalúe el modelo entrenado haciendo algunas predicciones.
Lo que aprenderás
Sintaxis de TensorFlow.js para crear modelos convolucionales con la API de capas de TensorFlow.js.
Formular tareas de clasificación en TensorFlow.js
Cómo monitorear el entrenamiento en el navegador usando la biblioteca tfjs-vis.
Lo que necesitarás
Una versión reciente de Chrome u otro navegador moderno que admita módulos ES6.
Un editor de texto, que se ejecuta localmente en su máquina o en la web a través de algo como Codepen o Glitch.
Conocimiento de HTML, CSS, JavaScript y DevTools de Chrome (o sus herramientas de desarrollo de navegadores preferidos).
Una comprensión conceptual de alto nivel de las redes neuronales. Si necesita una introducción o un repaso, considere ver este video de 3blue1brown o este video sobre Deep Learning en Javascript de Ashi Krishnan.
También debería sentirse cómodo con el material de nuestro primer tutorial de formación.

REFERENCIA: https://codelabs.developers.google.com/codelabs/tfjs-training-regression/index.html?hl=es-419#8