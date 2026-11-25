# Reconocimiento vehicular con red neuronal modular

Proyecto de **Redes Neuronales (redes no supervisadas)** · TecNM / ITESI.
Sistema que, con una cámara, identifica **marca, modelo, generación y año (2010–2026)** de un vehículo usando una red modular: detector **YOLO11**, rasgos **CLIP ViT-B/32**, una compuerta por marca, expertos por marca y un **mapa de Kohonen (SOM)**.

## Contenido de la carpeta

| Carpeta / archivo | Qué es |
|---|---|
| `presentacion/Red neuronal modular para reconocimiento vehicular.pdf` | Presentación de entrega (23 diapositivas, 16:9). |
| `presentacion/imagenes/` | Figuras usadas en la presentación (gráficas del SOM, U-matrix, capturas del programa y del conjunto de datos). |
| `documentos/YOLO11, CLIP y SOM en el proyecto.pdf` · `.docx` | Documento técnico: cómo se usan YOLO11, CLIP y el SOM en el proyecto. |
| `documentos/Guía de estudio - Red Neuronal Modular Vehicular.pdf` | Guía de estudio del sistema. |
| `documentos/Guía de estudio - Exposición del sistema de reconocimiento vehicular.pdf` | Guía para preparar la exposición. |
| `documentos/Documentación - Predictor de Autos con SOM de Kohonen.html` | Documentación del predictor con SOM (ábrela con el navegador). |

## Versiones editables (en Claude)

Las versiones originales y editables están en tu cuenta de Claude:

- Presentación (versión final, 31 oct): https://claude.ai/artifact/XrUAoAg3gwvdmBK5hoBBch
- Presentación (versión anterior, 27 oct): https://claude.ai/artifact/4k62f5k5ANLH7WZ86kRvFD
- YOLO11, CLIP y SOM en el proyecto: https://claude.ai/artifact/BEWwpetdWDJe7b2k8DeeT8
- Guía de estudio – Red Neuronal Modular Vehicular: https://claude.ai/artifact/RNMJKyd4hbeQjpR2nz9tWd
- Guía de estudio – Exposición: https://claude.ai/artifact/5uUbhngbXr9XE8wurpW5BJ
- Documentación del Predictor con SOM: https://claude.ai/artifact/SHbquAjUSpvGwaNwbV2xHH

> El PDF de la presentación se generó a partir de las diapositivas originales. Si notas alguna diferencia mínima de espaciado, exporta el PDF directamente desde la presentación en Claude (Compartir › Exportar).

## Pendiente para una entrega completa

- [ ] Agregar el **código fuente** (`vehiculo_temas4_mejorado.py`, `modulo_red_modular.py`, `modulo_referencias.py`) y un `requirements.txt`.
- [ ] Agregar los **pesos entrenados** (o un enlace a Hugging Face si superan 100 MB).
- [ ] Llenar el nombre del integrante en la portada.
