# Control-de-Leds-OpenCV-Python-Arduino
Circuito para controlar el encendido/apagado de LEDs mediante gestos con la mano usando python-OpenCv y Arduino.

🎬 **Demostración: [Video](https://youtube.com/shorts/k-IrpJlKAqU)**

### 🌟 Reconocimiento de gestos
El reconocimiento de gestos permite a las computadoras interpretar el lenguaje corporal humano, creando interfaces más intuitivas que van más allá de las GUI tradicionales. 

### 🔧 Implementación en este proyecto  
1. **Detección de gestos**: La biblioteca OpenCV se usa para reconocer los gestos de la mano. 
2. **Lógica**: Condiciones programadas en Python para encender/apagar los LEDs según la cantidad de dedos levantados.  
3. **Hardware**: Arduino recibe los datos mediante el protocolo Firmata y se controlan los LEDs. 

## 🖥️ Software 
- Python: versión 3.9.9
- OpenCV: librería CvZone
- Mediapipe
- Librería pyfirmata
- Arduino IDE y librería Firmata 

## ⚡ Componentes:
- Protoboard
- 5 Leds
- 5 resistencias de 220 Ω
- Arduino UNO
- Cables jumper

## 📐 Diagrama

![alt text](./Imagenes/diagrama.PNG)

## 🔌 Montaje en protoboard

![alt text](./Imagenes/esquematico.jpg)

### ⚠️ Nota sobre el código
Este proyecto parte de un código base de python. 
Los archivos pueden encontrarse en: https://drive.google.com/drive/folders/1lpK7rOpMgsS_1Y5xZwpXUH857NOpRDjX

El código de arduino (.ino) es generado utilizando el ejemplo StandardFirmata de la libreria Firmata, que proporciona el Arduino IDE.