Objetivo
El objetivo del reto será realizar un modelo predictivo basado en Random Forests que permita conocer el tipo de erupción que tendrá un volcán en función de las vibraciones medidas por los sensores.

Una vez se haya hecho y entrenado el modelo predictivo, este se tendrá que emplear con los features del dataset de testing 'jm_test_X.csv'. Estas predicciones se tendrán que entregar en formato csv como en el ejemplo. Donde tendrá que aparecer tan solo una columna en la que en la primera fila sea un texto cualquiera y las predicciones empiecen en la fila 2.

La calidad de la predicción se medirá a partir del f1-score (macro).# Repte_octubre

Datasets
Variables del dataset:

Features: El dataset contiene 6 features en 6 columnas, que son los parámetros medidos por los diferentes sensores. Estos corresponden a las vibraciones detectadas en ciertos puntos de la ladera del volcán.

Target: El target corresponde al 'label' que clasifica los tipos de erupciones volcánicas en función de los features medidos por los sensores.

* Target 0 corresponde a una erupción de tipo Pliniana
* Target 1 corresponde a una erupción de tipo Peleana
* Target 2 corresponde a una erupción de tipo Vulcaniana
* Target 3 corresponde a una erupción de tipo Hawaiana
* Target 4 corresponde a una erupción de tipo Estromboliana
