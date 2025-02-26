VigilantIA
================

Descripción
-----------

**VigilantIA** es un sistema de visión artificial basado en YOLOv8 para la detección de personas sin casco de seguridad en entornos laborales.

Características
---------------

*   Detección en tiempo real de trabajadores sin casco.
    
*   Uso de **YOLOv8** para la detección de objetos.
    
*   Implementado con **Python, OpenCV y Ultralytics**.
    

Instalación
-----------

### Prerrequisitos

*   Python 3.8+
    
*   pip
    

### Dependencias

Ejecuta el siguiente comando para instalar las librerías necesarias:

```bash
pip install opencv-python ultralytics torch torchvision
```

Uso
---

### Para probar con una imagen

```bash
python vigilantia.py test_image.jpg
```

Futuras Mejoras
---------------

*   Entrenamiento de un modelo especializado en cascos.
    
*   Implementación en video en tiempo real.
    
*   Integración con sistemas de alerta.
    

Contribuciones
--------------

Las contribuciones son bienvenidas. Si quieres mejorar **VigilantIA**, crea un _pull request_ o reporta un _issue_.

Licencia
--------

MIT License
