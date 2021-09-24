# Machine-Learning-e-imagenes

### 1 Binarización: Clasificación dentro de una imagen en 2 clases, utilizando una variable: intensidad

Cargar en la notebook utilizando la librería OpenCV una imagen de manera monocroma que contenga un objeto claro u oscuro a destacar del fondo y luego:

* Binarizar la imagen por umbralado de la intensidad (utilizar el histograma de ser necesario para la elección del umbral), buscando separar el objeto deseado del fondo (unos,255 o rue en el objeto y ceros o False en el fondo).
* Mejorar la binarización con un filtro morfológico que crea adecuado.
* Encontrar los bordes del objeto utilizando operaciones morfológicas o gradiente morfológico.

### 2 Clasificación dentro de una imagen: 4 clases, 3 variables o features: R,G,B

Cargue una imagen RGB a elección que a la vista tenga 4 clases identificables:

* Utilice k-medias con k=4 cantidad de clusters para realizar clasificación no supervisada de la imagen. Muestre los resultados, tanto en el espacio RGB como en la disposición de los clusters encontrados en la imagen.
* Realice una clasificación semi-supervisada: 
 - etiquetando manualmente pixeles de las 4 clases. muestre los pixeles etiquetados en el espacio RGB. 
 - reclasificando toda la imagen según esas cuatro clases.
 - Muestre los resultados y realice una mejora de la clasificación utilizando un filtro de moda


### 3 Redes Neuronales
Considerando la base de datos mnist
* Utilice **dos** redes totalmente conectadas (fully conected) para clasificar cada imagen en los 10 tipos de dígitos y compárelas en cuanto a su desempeño y overfitting (sobreajuste a los datos de entrenamiento y mal ajuste en los datos de test).
* Utilice **dos** redes neuronales convolucionales para clasificar cada imagen en los 10 tipos de dígitos y compárelas en cuanto a su complejidad (cantidad de parámetros) y overfitting. Comente resultados
* Realice aumentación de datos utilizando una rotación de +5 y -5 grados de cada imagen.
