# Machine-Learning-e-imagenes

### 1 Binarización: Clasificación dentro de una imagen en 2 clases, utilizando una variable: intensidad

Cargar en la notebook utilizando la librería OpenCV una imagen de manera monocroma que contenga un objeto claro u oscuro a destacar del fondo y luego:

* Binarizar la imagen por umbralado de la intensidad (utilizar el histograma de ser necesario para la elección del umbral), buscando separar el objeto deseado del fondo (unos,255 o rue en el objeto y ceros o False en el fondo).
* Mejorar la binarización con un filtro morfológico que crea adecuado.
* Encontrar los bordes del objeto utilizando operaciones morfológicas o gradiente morfológico.
