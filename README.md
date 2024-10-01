# Proyecto Ironhack Payments:
### Definicion del problema: Cual es el comportamiento de los usuarios teniendo en cuenta su primer adelanto en efectivo?
### Objetivos: Analizar

#Importamos la libreria pandas como pd

>import pandas as pd

#Creamos los paths correspondientes a cada BBDD

>file_path="/Users/SESA779631/Desktop/projectIron/cash.csv" (cambiar el path si corresponde)

>file_path_extract="/Users/SESA779631/Desktop/projectIron/extract.csv" 

#Guardamos los documentos en dataframes (cash y extract)

>df_cash=pd.read_csv(file_path)

>df_extract=pd.read_csv(file_path_extract)

#Mostramos las primeras lineas de df_cash y df_extract para conocer las columnas (variables) y ir viendo que y como se limpiara

>df_cash.head()

>df_extract.head()

