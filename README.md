# Time.Series-Analysis-Wk
Análisis de series temporales de datos desde cero. También implemento el modelo autorregresivo (AR), el modelo de media móvil (MA), el modelo de media móvil autorregresiva (ARMA), el modelo de media móvil autorregresiva integrada (ARIMA), el modelo ARCH, el modelo GARCH, Auto ARIMA, pronósticos y explorar un caso de negocio.

Memories for Analysis on Time Series for finance

En el script 0 contiene a la extraccion de los datos
En el script 1 se tendra que usar la base de datos llamada Index_2018,que contiene a los datos de los mismos indices financieros entre 1994 a 2018 luego se extraido los datos hasta fecha actual o fecha hasta donde esta publicada en Yahoo Finance,posteriormente se ha conectado mediante
En el script 2 se varia demasiado la frecuencia prefererida asi aque se considero otra variable 
En el script 3 no correr la importacion de Random walk,ya que existe archivo encontrado
En el script 4 necesitamos la data de RandowWalk.csv,sin embargo esta no existente,pues se añade al dataframe original que se importa en Index_2018.csv ahora llamado Index_modified.csv,por ello es que solo se comentara cada linea de codigo.Modificacion de libreria nueva
from statsmodels.tsa.arima.model import ARIMA
En el script 5 esta todo completado con teoria 
del script 6 al 12 listo solo falta comentar
Importante:
En cada script usar la data Index_modified.csv y correr el siguiente codigo df_comp.set_index("date", inplace=True)
Modificar la liberia en cada libreria asi 
from statsmodels.tsa.arima.model import ARIMA
Usar ARIMA,en lugar de arma,y la estructura sera (p,i,q)
p= Rezagos Modelo AR
i = diferencias Modelo ARIMA
q = Errores Modelo MA