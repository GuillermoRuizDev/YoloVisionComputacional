# Yolov3 Vision Computacional PUCP IA 2020
Proyecto Yolo de Visión Computacional

Detección de objetos en tiempo real_YOLO
Detección de objetos en tiempo real utilizando el algoritmo Darknet YOLO (solo mira una vez), OpenCV en el conjunto de datos COCO (objetos comunes en contexto).

Implementación
Darknet YOLOv3 se ha utilizado junto con los pesos preconfigurados YOLOv3 para el mismo clip. El clip de salida se recibe a aproximadamente 8 FPS.

FPS creciente
Las operaciones como recuperar video de la cámara web son intensivas en E / S, utilizamos el enhebrado (imutil.py) para utilizar un hilo separado para las operaciones relacionadas con E / S y terminan en una velocidad de cuadro muy aumentada.

Salida
El video de salida se genera a través de VideoWriter de OpenCV a output_clip.mp4.
