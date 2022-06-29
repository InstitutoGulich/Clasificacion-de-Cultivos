# Clasificacion-de-Cultivos
Clasificación de cultivos

El presente còdigo se encuentra disponible para Jupyter.

Requiere de una cuenta en Google Earth Engine

El usuario puede indicar la zona donde se trabajarà y los datos a utilizar para el entrenamiento
Se debe modificar las siguiente lìneas

## # Se carga el vector con el área/s a clasificar (Desde la PC o asset de GEE)
area = ee.FeatureCollection('users/COMPLETAR')
## # Se carga el vector con los datos de referencia a terreno (para entrenar y validar)
rdata = ee.FeatureCollection('users/COMPLETAR')

