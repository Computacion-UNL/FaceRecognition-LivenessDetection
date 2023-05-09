# Prototipo de reconocimiento facial con detección de vida para el registro de asistencias en el laboratorio de software de CIS/C UNL.

![registrado](https://github.com/Computacion-UNL/FaceRecognition-LivenessDetection/assets/46323169/8a028adb-6e73-4091-82e7-c9a3b0f2fa32)

------------
## Tabla de Contenidos:
- [Autor](#autor)
- [Descripción y Contexto](#descripción-y-contexto)
- [Información adicional](#información-adicional)

## Autor:
El presente Trabajo de Titulación fue desarrollado por:
- Dayanna Magdalla Alvarado Castillo - dayanna.alvarado@unl.edu.ec

Con la dirección de:
- Ing. Oscar Miguel Cumbicus Pineda, Mg. Sc. - oscar.cumbicus@unl.edu.ec

## Descripción y Contexto:
El presente repositorio contiene el código del proyecto de Titulación denominado **"Prototipo de reconocimiento facial con detección de vida para el registro de asistencias en el laboratorio de software"** de la Carrera de Ingeniería en Sistemas/Computación de la Universidad Nacional de Loja.

El repositorio contiene 3 directorios: 
1. **Detección de vida:** Esta carpeta contiene los modelos con los que se experimentó la detección de vida, contiene el modelo desarrollado para el análisis de profundidad y el contador de parpadeos, dentro de estos directorios se encuentra el archivo ejecutable .py y un archivo TEST.md, en este último se ubican algunos ejemplos de la experimentación.
2. **Reconocimiento facial:** Esta carpeta contiene los modelos con los que se experimentó el reconocimiento facial. En el caso del directorio  "Modelos Eigen-Face, Fisher-Faces y LBPH-Face" contiene el archivo captura.py el cual es útil para capturar los frames necesarios para la base de datos, dentro del directorio de cada modelo, a más del archivo de reconocimiento se encuentra también el archivo que contiene código necesario para el entrenamiento. En el subdirectorio "Modelo Face-Recognition" se encuentra el archivo ejecutable para llevar a cabo el reconocimiento facial.
3. **Asistencias:** Este directorio almacena el módulo web de registro de asistencias con reconocimiento facial y detección de vida, desarrollado en Odoo v13, se trata del prototipo final que contiene el modelo Face-Recognition y el modelo de análisis de profundidad.


## Información adicional: 
Para conocer más de Odoo ingrese a https://www.odoo.com/es_ES/  

Para acceder a la documentación de Desarrolladores de Odoo ingrese a https://www.odoo.com/documentation/13.0/

Para instruirse en el desarrollo en Framework Odoo ingrese a https://escuelafullstack.com/slides/curso-de-odoo-13-framework-backend-2
