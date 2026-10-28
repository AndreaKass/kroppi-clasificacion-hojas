# kroppi-clasificacion-hojas
Clasificación preliminar de enfermedades foliares del café mediante inteligencia artificial y visión por computador.
# Kroppi

**Sistema de detección preliminar de enfermedades foliares mediante inteligencia artificial y visión por computador.**

## Descripción

Kroppi es un proyecto académico que busca desarrollar una herramienta para realizar la clasificación preliminar de enfermedades foliares mediante el análisis de imágenes y modelos de inteligencia artificial.

El sistema está orientado inicialmente a imágenes de hojas de maíz. Sus resultados constituyen una orientación preliminar y no reemplazan la evaluación de un especialista.

## Objetivo

Desarrollar un sistema basado en visión por computador que permita clasificar imágenes de hojas utilizando modelos de inteligencia artificial y, posteriormente, integrar el modelo seleccionado en un prototipo funcional de Kroppi.

## Dataset

El proyecto utiliza un conjunto de datos de hojas de maíz con las siguientes categorías:

- `Blight`
- `Common_Rust`
- `Gray_Leaf_Spot`
- `Healthy`

**Fuente:** dataset de enfermedades de hojas de maíz de Kaggle, asociado a Smaranjit Ghose.

Las cantidades de imágenes, las estadísticas y la división de los datos se documentarán a partir de los resultados comprobados del notebook.

El dataset no se incluye necesariamente en este repositorio. Consulta las instrucciones de obtención y las condiciones de uso de la fuente original.

## Tecnologías

Las tecnologías y bibliotecas definitivas se registrarán según las que se hayan utilizado realmente en el notebook.

## Estructura del repositorio

- `notebooks/`: notebooks de exploración, preparación y entrenamiento.
- `results/`: gráficas, métricas y resultados experimentales.
- `data/`: instrucciones para obtener los datos.
- `README.md`: descripción e instrucciones del proyecto.
- `.gitignore`: archivos excluidos del control de versiones.
- `requirements.txt`: dependencias de Python.

## Metodología

El trabajo contempla las siguientes actividades:

1. Análisis exploratorio del dataset.
2. Preparación y partición de las imágenes.
3. Implementación de modelos de clasificación.
4. Entrenamiento y experimentación.
5. Evaluación cuantitativa y comparación de modelos.
6. Integración posterior del modelo seleccionado en Kroppi.

Esta lista describe la metodología prevista; el avance real se documentará con los experimentos ejecutados.

## Resultados

En esta sección se incorporarán las métricas, tablas y gráficas generadas durante los experimentos, junto con su interpretación.

No se incluyen resultados numéricos hasta verificar las salidas del notebook.

## Limitaciones

El modelo estará limitado a las categorías de entrenamiento y a la calidad y representatividad de las imágenes disponibles. Sus predicciones no constituyen un diagnóstico fitosanitario definitivo.

## Autora

Andrea Katiana Sierra Sanchez

Proyecto académico de Ingeniería de Sistemas.
