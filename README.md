# cnn_water_segmentation
Código fuente para la segmentación de cuerpos de agua en imágenes satelitales (PlanetScope) mediante U-Net. 

## Descripción
El sistema procesa imágenes satelitales mediante una estrategia de *Tiling* (ventanas deslizantes), permitiendo cuantificar la superficie de la laguna de Yahuarcocha con alta precisión y realizar un análisis multitemporal (2016-2025).

## Estructura del Código
* `src/preprocessing.py`: Generación de máscaras y dataset (Tiling).
* `src/train_unet.py`: Entrenamiento de la red neuronal.
* `src/inference_pipeline.py`: Script principal de inferencia automatizada.
* `src/metrics_calc.py`: Cálculo de área y métricas de error.

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
