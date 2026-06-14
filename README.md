# Código del TFG

## Descripción

Este repositorio contiene la parte computacional de un Trabajo de Fin de Grado sobre modelos de aprendizaje automático basados en árboles de decisión.

## Contenido

El contenido se separa en dos bloques:

* `notebooks/comparativa_modelos/`: comparativa experimental principal con los conjuntos de datos reales del trabajo.
* `notebooks/ejemplos_didacticos/`: ejemplos independientes para ilustrar el funcionamiento de CART, Bagging y Boosting con conjuntos de datos clásicos de `scikit-learn`.

## Orden de ejecución

Para reproducir la comparativa principal, se recomienda ejecutar los notebooks en este orden:

1. Preprocesamiento de Bank Marketing.
2. Preprocesamiento del consumo eléctrico.
3. Modelos CART.
4. Modelos de Bagging.
5. Modelos de Boosting.
6. Comparación computacional.

Los ejemplos didácticos son independientes de esta secuencia y pueden ejecutarse por separado.

## Datos

La comparativa principal utiliza dos conjuntos de datos procedentes de UCI Machine Learning Repository:

* Bank Marketing: https://archive.ics.uci.edu/dataset/222/bank+marketing
* Individual Household Electric Power Consumption: https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption

Los datos no se almacenan en este repositorio. Los notebooks de preprocesamiento descargan los archivos desde las URL oficiales de UCI.

## Ejemplos didácticos

Los ejemplos didácticos utilizan conjuntos de datos incluidos en `scikit-learn`:

* Iris, para ilustrar un árbol CART de clasificación.
* Breast Cancer Wisconsin Diagnostic, para comparar de forma didáctica métodos de Bagging y Boosting.

Estos ejemplos no forman parte de la comparativa experimental principal.

## Entorno

Para instalar las dependencias mínimas:

```bash
pip install -r requirements.txt
```

Después, los notebooks pueden abrirse y ejecutarse con Jupyter Notebook o JupyterLab.

## Estado

Los notebooks se incluyen con salidas visibles para facilitar su revisión en GitHub. Las explicaciones pueden seguir ajustándose durante el desarrollo final del TFG.
