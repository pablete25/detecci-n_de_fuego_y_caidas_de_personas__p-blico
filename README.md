# Detección de fuego y caídas de personas con YOLOV8
Proyecto de detección de fuego y caídas de personas con YOLOV8 y OpenCv
## 1. Introducción y Objetivo del proyecto
El objetivo del proyecto es desarrollar un programa que detecte fuego y caidas de personas en tiempo real , cuando ocurra alguna de estas dos cosas nos debe avisar mandando un mensaje al teléfono móvil. Para la detección del fuego a tiempo real vamos a utilizar OpenCV con YOLO v8. Para que nos avise avise el telefono vamos emplear la API de telegram para recibir un mensaje a nuestro Telegram. Al detectar fuego, también se activara un alarma de emergencia de forma local. Para detectar la caida de personas vamos a utilizar el modelo de YOLOv8s sin entrenar y operaremos sobre el mismo en la clase personas.

Para la detección de fuego, podremos usar dos modelos preentrenados de YOLO v8:
- Modelo de detección de fuego.
- Modelo de detección de fuego y humo.

El programa esta pensado para la monitorización de casas donde viven personas dependientes, como ancianos o minusvalidos. 
## 2. Instalación de dependencias
Es recomendable instalar las dependencias en un entorno conda o miniconda. Una vez dentro de ese entorno ejecutar lo siguiente en la terminal:
```bash
pip install -r requirements.txt
```
