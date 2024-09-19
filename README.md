# CLASIFICACIÓN DE IMÁGENES  DE CÁNCER DE MAMA UTILIZANDO UN MODELO DE REDES NEURONALES CONVOLUCIONALES
CLASIFICACIÓN DE IMÁGENES HISTOLÓGICAS DE CÁNCER DE MAMA UTILIZANDO UN MODELO DE REDES NEURONALES CONVOLUCIONALES

Este proyecto tiene como objetivo desarrollar un modelo de Machine Learning para la clasificación de imágenes histopatológicas, con el propósito de detectar la presencia de carcinoma ductal invasivo (IDC) en tejidos mamarios. El carcinoma ductal invasivo es un tipo común de cáncer de mama, y la detección temprana es clave para mejorar las tasas de supervivencia. Utilizando un conjunto de datos de imágenes de histopatología descargado de Kaggle, que contiene imágenes etiquetadas como "IDC" (cáncer presente) y "No IDC" (sin cáncer), se procesaron las imágenes para su posterior análisis y modelado.
El proyecto aborda varios desafíos clave, como el desequilibrio de clases en el conjunto de datos, ya que hay más del doble de imágenes "No IDC" en comparación con "IDC". Las imágenes, uniformemente dimensionadas a 50x50 píxeles con tres canales de color, fueron analizadas en términos de sus propiedades estadísticas, como la intensidad de color. Esta información proporcionó una visión importante sobre las características de las imágenes, lo que permitirá ajustar el enfoque de modelado. La metodología se enfoca en el uso de redes neuronales convolucionales (CNNs) para realizar la clasificación automática de estas imágenes, buscando maximizar la precisión en la detección de IDC.



CONCLUSIÓN
Este proyecto ha demostrado la viabilidad de utilizar redes neuronales convolucionales (CNNs) para la detección automatizada de carcinoma ductal invasivo (IDC) en imágenes histopatológicas de cáncer de mama. A lo largo del desarrollo, se han aplicado diversas técnicas y metodologías para mejorar la precisión del modelo y superar los desafíos inherentes al desequilibrio de clases y el manejo de grandes volúmenes de datos.
Uno de los primeros pasos clave fue la preparación del conjunto de datos, que incluía tanto imágenes con presencia de IDC como sin ella. Debido al marcado desequilibrio entre ambas clases, se aplicaron técnicas de Data Augmentation para generar nuevas imágenes y equilibrar el conjunto de datos. Esto permitió entrenar un modelo con mayor capacidad de generalización y evitar sesgos hacia la clase mayoritaria.
El modelo se construyó utilizando la arquitectura DenseNet-121, seleccionada por su capacidad para extraer características detalladas de las imágenes. Se realizaron varias optimizaciones, incluyendo el uso de Dropout y Batch Normalization para prevenir el sobreajuste. Durante el entrenamiento, el modelo mostró mejoras continuas en precisión, alcanzando una precisión final de 84.54% en el conjunto de validación.
La evaluación del modelo se realizó mediante una matriz de confusión, que permitió analizar tanto los aciertos como los errores de clasificación. Los resultados indicaron que, si bien el modelo tiene un buen rendimiento general, es necesario seguir trabajando en la reducción de los falsos negativos, dado que estas clasificaciones incorrectas tienen un impacto significativo en el diagnóstico de enfermedades críticas como el cáncer.
Finalmente, el modelo se encapsuló en una aplicación de escritorio en formato .exe para facilitar su uso por parte de médicos y profesionales de la salud. La
aplicación permite cargar imágenes, realizar el análisis de manera automática y generar un resultado en texto con el diagnóstico. Esta herramienta tiene el potencial de ser utilizada como un sistema de apoyo en la detección de cáncer, aunque debe ser complementada con la evaluación de un especialista.
18
En conclusión, este proyecto no solo ha demostrado la capacidad de las CNNs para resolver problemas complejos en el ámbito médico, sino que también ha creado una solución práctica para apoyar a los profesionales de la salud en la detección temprana de cáncer de mama. Sin embargo, futuras mejoras deben centrarse en optimizar aún más la precisión del modelo y reducir el tiempo de procesamiento en entornos de baja capacidad de memoria, como Google Colab.



ANEXO

Link Data set Originak
https://drive.google.com/drive/folders/1LYHrc5_IHeg6uT70PFIdHhIm4UGroc 00?usp=sharing

Link del Dataset con las imágenes redimensionadas 224
https://drive.google.com/drive/folders/1U5OxqbwfsW4eTr7aZW1eFqAmHGm StLUd?usp=sharing

Link del Data frame con las imágenes 224px
https://drive.google.com/file/d/1Df-KXieRh2FbvabregRHl3b94Uf3sWrO/view? usp=sharing

Link al NoteBook de Google Colab
https://colab.research.google.com/drive/12wDiu1bhkRGaIlsW85iNBVe_-3eLX 6MC?usp=sharing

Link del Modelo Exportado en extensión h5
https://drive.google.com/file/d/1LlPPSGtAhvy2-ht0HNIYcodqc42cHie1/view? usp=sharing

Link del Codigo para la app de Escritorio .EXE
https://drive.google.com/file/d/1LlPPSGtAhvy2-ht0HNIYcodqc42cHie1/view? usp=sharing

Link al video del Proyecto
https://drive.google.com/file/d/1RNgvwDfhKXJUO8ZN6ugVhLVsFOjWqO4X /view?usp=sharing

Link a la Presentación del Proyecto
https://docs.google.com/presentation/d/1C4aukotpfiLWvqs3zqq0xHlAsy53wo1 rt7_2IxCOqb4/edit?usp=sharing
