# 1. Introducción
En este laboratorio de código, entrenará un modelo para hacer predicciones a partir de datos numéricos que describen un conjunto de automóviles.

Este ejercicio demostrará los pasos comunes para entrenar muchos tipos diferentes de modelos, pero usará un pequeño conjunto de datos y un modelo simple (superficial). El objetivo principal es ayudarlo a familiarizarse con la terminología básica, los conceptos y la sintaxis de los modelos de entrenamiento con TensorFlow.js y proporcionar un trampolín para una mayor exploración y aprendizaje.

Debido a que estamos entrenando un modelo para predecir números continuos, esta tarea a veces se denomina tarea de regresión. Entrenaremos el modelo mostrándole muchos ejemplos de entradas junto con la salida correcta. Esto se conoce como aprendizaje supervisado.

Que vas a construir
Creará una página web que use TensorFlow.js para entrenar un modelo en el navegador. Dada la "potencia" de un automóvil, el modelo aprenderá a predecir las "millas por galón" (MPG).

# Para hacer esto usted:

Cargue los datos y prepárelos para el entrenamiento.
Definir la arquitectura del modelo.
Entrene al modelo y controle su rendimiento mientras entrena.
Evalúe el modelo entrenado haciendo algunas predicciones.
Lo que aprenderás
Mejores prácticas para la preparación de datos para el aprendizaje automático, incluida la reproducción aleatoria y la normalización.
Sintaxis de TensorFlow.js para crear modelos con la API tf.layers.
Cómo monitorear el entrenamiento en el navegador usando la biblioteca tfjs-vis.
Lo que necesitarás
Una versión reciente de Chrome u otro navegador moderno.
Un editor de texto, que se ejecuta localmente en su máquina o en la web a través de algo como Codepen o Glitch.
Conocimiento de HTML, CSS, JavaScript y DevTools de Chrome (o sus herramientas de desarrollo de navegadores preferidos).
Una comprensión conceptual de alto nivel de las redes neuronales. Si necesita una introducción o un repaso, considere ver este video de 3blue1brown o este video sobre Deep Learning en Javascript de Ashi Krishnan.