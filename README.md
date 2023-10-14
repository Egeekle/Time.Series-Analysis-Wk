# Time.Series-Analysis-Wk
Análisis de series temporales de datos desde cero. También implemento el modelo autorregresivo (AR), el modelo de media móvil (MA), el modelo de media móvil autorregresiva (ARMA), el modelo de media móvil autorregresiva integrada (ARIMA), el modelo ARCH, el modelo GARCH, Auto ARIMA, pronósticos y explorar un caso de negocio.

Memories for Analysis on Time Series for finance

En el script 0 contiene a la extraccion de los datos
En el script 1 se tendra que usar la base de datos llamada Index_2018,que contiene a los datos de los mismos indices financieros entre 1994 a 2018 luego se extraido los datos hasta fecha actual o fecha hasta donde esta publicada en Yahoo Finance,posteriormente se ha conectado mediante
En el script 2 se varia demasiado la frecuencia prefererida asi aque se considero otra variable 
En el script 3 no correr la importacion de Random walk,ya que existe archivo encontrado
Importante:
En cada script usar la data Index_modified.csv y correr el siguiente codigo df_comp.set_index("date", inplace=True)
