![UPC](https://github.com/Shark7EnzoCamargo/TF-Imagenes/assets/89089765/c7cc0276-acf8-4da8-baa9-9fd012b10f7b)

# Universidad Peruana de Ciencias Aplicadas
## Procesamiento de Imágenes - CC235
### Trabajo Final

Sección: CC61
Profesor: Peter Jonathan Montalvo Garcia

Alumno: Camargo Ramírez, Enzo Fabricio (U202010122)

## Introducción
Para este trabajo final, decidí desarrollarlo de forma individual. Los videos fueron grabados en el pasillo entre el pabellón A y el pabellón E del campus de Monterrico. Para este proyecto se realizó una exhaustiva investigación respecto a las diferentes versiones de YOLO, para determinar cuál utilizaría en el presente trabajo.

En esta oportunidad decidí implementar Ultralytics YOLOv8, el cual es la última versión de este algoritmo, sobre todo al momento de detectar objetos de cualquier tamaño en tiempo real. Se grabaron 2 videos para este trabajo, en donde decidí poner a prueba la capacidad de detección de YOLOv8, ya que al primer video le reduje su calidad a 480 píxeles, caso contrario al segundo video que lo mantuve en 720 píxeles.

## Objetivos
- Detectar el movimiento continuo de las personas
- Conocer el porcentaje de aprobación respecto a si el programa reconoce a una persona
- Implementar un contador para clasificar a las personas que recorren el pasillo hacia arriba o hacia abajo

## Resultados

Video 1 - original

![video1](https://github.com/Shark7EnzoCamargo/TF-Imagenes/assets/89089765/82a72d61-8ff0-4295-9d7c-aa448d618c97)

Video 1 - resultado

![video1-r](https://github.com/Shark7EnzoCamargo/TF-Imagenes/assets/89089765/18dfd6df-69c3-4890-a614-b057c1e719d7)

Se puede apreciar que a pesar de la baja calidad de video, se detecta correctamente a cada una de las personas gracias al entrenamiento previo realizado



Video 2 - original

![video2](https://github.com/Shark7EnzoCamargo/TF-Imagenes/assets/89089765/c3f62703-4a6a-47e6-bebf-235e2cee7b6f)

Video 2 - resultado

![video2-r](https://github.com/Shark7EnzoCamargo/TF-Imagenes/assets/89089765/71751b75-8284-4b07-9ccf-453c73fa093b)

En este segundo video se puede apreciar que también funciona adecuadamente la detección de las personas. Además, el “out” lleva el valor de 1, lo cual es el contador que aumenta cuando una persona cruza la línea horizontal a la dirección a la que se dirige. En este caso, se contó a la chica que caminaba hacia la dirección de abajo.
