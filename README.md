# Herramientas Computacionales: El Arte de la Programación
Aqui yacen las esperanzas de un ingeniero en mecatronica.

Este repositorio contiene las actividades y proyectos desarrollados durante la Semana Tec "Herramientas Computacionales: El Arte de la Programación". El objetivo es explorar diversas áreas de la inteligencia artificial, incluyendo visión por computadora y machine learning.

Las actividades realizadas en clase se encuentran en la rama "main", adicionalmente cada actividad tiene su rama independiente.

## Contenido del Repositorio

El repositorio está organizado en carpetas, cada una correspondiente a una actividad o tema específico.

### Actividad 1: Introduccion a Github
Esta carpeta no contiene nada relevante, su unico proposito era la creacion de ramas para familiarisarze con la plataforma.

- **`image_capture.py`**: Codigo de prueba hecho en python que detecta imamgenes.

### Actividad 2: Visión por Computadora con OpenCV

- **`HerramientasVision.ipynb`**: Notebook con una introducción a las herramientas básicas de visión por computadora utilizando OpenCV. Cubre temas como:
    - Lectura y manipulación de imágenes.
    - Filtros (Gaussiano, mediana, bilateral).
    - Detección de bordes (Canny, Sobel, Laplaciano).
    - Detección de características (Harris, Shi-Tomasi, ORB).
    - Detección de círculos con la transformada de Hough.
- **`ejemplo_opencv.ipynb`**: Otro ejemplo práctico de uso de OpenCV.

### Actividad 3: Machine Learning Básico

- **`RedesNeuronales.ipynb`**: Implementación de una red neuronal para la clasificación del dataset MNIST utilizando Keras/TensorFlow.
- **`ejemplo_opencv.ipynb`**: Otro ejemplo práctico de uso de MNIST.
## Cómo Empezar

Para ejecutar los notebooks de este repositorio, sigue estos pasos:

1.  **Clona el repositorio:**
    ```bash
    git clone <URL-del-repositorio>
    cd HerramientasComputacionales
    ```

2.  **Crea un entorno virtual (recomendado):**
    ```bash
    python -m venv venv
    ```
    Y actívalo:
    - En Windows: `.\venv\Scripts\activate`
    - En macOS/Linux: `source venv/bin/activate`

3.  **Instala las dependencias:**
    Se recomienda instalar las librerías a medida que las necesites. Las principales son:
    ```bash
    pip install jupyter numpy matplotlib opencv-python tensorflow scikit-learn
    ```

4.  **Ejecuta Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
    Desde la interfaz de Jupyter, navega a la carpeta de la actividad que desees explorar y abre el archivo `.ipynb`.