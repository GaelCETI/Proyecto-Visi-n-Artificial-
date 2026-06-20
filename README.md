# Sistema de Clasificación Automatizada de Autopartes mediante Visión Artificial (YOLO)

## 👥 Integrantes
* **Gael Jesús Muñoz Aviña** - Registro: 23110193
* **David Israel Rodríguez Medina** - Registro: 22310261

---

## 🎯 Objetivo del Proyecto
Aplicar los conceptos de Visión Artificial mediante el entrenamiento de un modelo de la familia YOLOv11s (You Only Look Once) para la detección y clasificación en tiempo real de diferentes piezas automotrices en una línea de producción.
Esto mediante un primer etiquedado de imagenes de un dataset que le permite al modelo tener una referencia de que objetos corresponden a el encabezado asignado.
**Posteriormente el modelo yolo es entrenado con un Labeling pensado especificamente para este modelo.
**El sistema identificará el tipo de componente y coordinará la separación física de los mismos hacia bandas transportadoras secundarias dedicadas, optimizando el flujo de logística y empaque en la fábrica.
**De forma visual podemos generar imagenes donde el modelo automaticamente con el aprendizaje obtenido determina y sepera por bloques cada uno de los componentes para asi poder comprender el acondicionamiento del modelo.

---

## 🛠️ Configuración del Entorno e Instalación

Para ejecutar y probar el código de este proyecto de manera local, sigue los pasos descritos a continuación:

### 1. Requisitos Previos
Asegúrate de tener instalado Python 3.8 o superior y el gestor de paquetes `pip`.

### 2. Clonar el Repositorio
```bash
git clone [https://github.com/tu-usuario/tu-repositorio.git](https://github.com/tu-usuario/tu-repositorio.git)
cd tu-repositorio
