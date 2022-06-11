# MCDA-PI1-G6
Proyecto: Predicción de precios de vivienda nueva en la ciudad de Medellín mediante métodos de aprendizaje supervisado

## Contexto
El presente proyecto toma fuentes de información de la venta de viviendas y sus características (area, muros, estructura, etc...) desde el 2017 hasta el 2022


### Instrucciones para correr el proyecto
Para llevar a cabo la ejecución del proyecto se deben tener en cuenta las siguientes recomendaciones:
- Asegurarse de actualizar en la primera sección de los Jupyter Notebooks las claves de acceso: (Access Key, Secret Key, Session Token)
- Los datos deben estar en el DataLake de AWS

Los notebooks se deben correr en el siguiente orden:
* 01_Descripcion_BaseFormulada.ipynb
* 01_Descripcion_ServComple.ipynb
* 02_Limpieza_BaseFormulada.ipynb
* 02_Limpieza_ServComplementarios.ipynb
* 03_InnerJoin.ipynb
* 04_Descripcion_TablaUnida.ipynb
* 05_Modelos_PrecioInflacion.ipynb
* 05_Modelos_PrecioDeflaccionado.ipynb

