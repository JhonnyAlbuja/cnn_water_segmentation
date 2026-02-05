# Segmentación de Superﬁcies Acuáticas en Imágenes Satelitales mediante Redes Neuronales Convolucionales: Aplicación en Yahuarcocha
Código fuente para la segmentación de cuerpos de agua en imágenes satelitales (PlanetScope) mediante U-Net. 

## Descripción
El sistema procesa imágenes satelitales mediante una estrategia de *Tiling* (ventanas deslizantes), permitiendo cuantificar la superficie de la laguna de Yahuarcocha con alta precisión y realizar un análisis multitemporal.

## Estructura del Código
* `src/Tiling.ipynb`: Recorta las máscaras e imagenes en tamaños de 256x256 (Tiling).
* `src/train_unet.ipynb`: Entrenamiento de la red neuronal.
* `src/dataaugmentatio.ipynb`: Script para aumentrar la cantidad de datos de manera autónoma
* `src/split_dataset.ipynb`: Genera rotaciones, splits, aumentos de contraste y brillo.
* `src/metrics_calc.ipynb`: Cálculo de área y métricas de error.

## Requisitos
El código fue desarrollado en Python 3.10. Las dependencias principales son:
* TensorFlow / Keras
* Rasterio
* NumPy
* OpenCV
* Matplotlib

## Autor
**Jhonny Albuja Andrade**
Universidad Técnica del Norte (Ibarra, Ecuador)
2026
