# Analitica
Ejercicio fastApy
Despliegue de un Modelo de Clasificación con FastAPI + ngrok en Google Colab

Este proyecto demuestra cómo entrenar, desplegar y consumir un modelo de clasificación de flores Iris usando:

- `scikit-learn`
- `FastAPI` para exponer una API REST
- `ngrok` para hacer la API accesible públicamente desde Google Colab


# Funcionalidad

La API permite realizar predicciones sobre la especie de una flor Iris a partir de sus medidas, Retorna tanto la clase como las probabilidades estimadas para cada una.

# Entrada esperada (`POST /predict`)

```json
{
  "features": [1, 1, 2, 1]
}
En esta tabla se ve como tal lo que significaría cada dato que se envia que seria lo de la descripcion
Índice	Característica	Descripción	Unidad
0	sepal length 	Largo del sépalo	cm
1	sepal width 	Ancho del sépalo	cm
2	petal length 	Largo del pétalo	cm
3	petal width 	Ancho del pétalo	cm


Aca se muestra la api en función corriendo desde colab
 

Aca se ven los ejemplos que se realizaron en postman con dos ejemplos de cómo funciona la api

 
 
