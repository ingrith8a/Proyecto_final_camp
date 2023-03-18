Autor/a: <Ingrith Marcela Ochoa Bernal>
Hola 
En este documento encontrara el paso a paso para ejecutar de manera satisfactoria el trabajo realizado como proyecto final

Preparar el ambiente

Para preparar el ambiente de ejecución se deben realizar (solo la primera vez) los siguientes pasos

1. importar las siguientes bibliotecas

import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import sklearn
import matplotlib.pyplot as plt

from scipy.spatial.distance import cdist
from sklearn.cluster import KMeans
from sklearn.preprocessing import StandardScaler
from scipy.stats import pearsonr, spearmanr
from sklearn.linear_model import LinearRegression
from sklearn.model_selection import train_test_split
from sklearn.metrics import silhouette_samples, silhouette_score, mean_squared_error


plt.rcParams['image.cmap'] = "bwr"
plt.rcParams['savefig.bbox'] = "tight"
plt.style.use('ggplot')
plt.rcParams['image.cmap'] = "bwr"
plt.rcParams['savefig.bbox'] = "tight"
plt.style.use('ggplot')


Lectura del dataset 

2. En git hub encontrara una carpeta llamada Proyecto final, dentro de esta carpeta encontrara la data que debe descargar en su equipo con nombre "country_wise_latest.csv"

  - En la línea 11 se debe referenciar la ruta en la cual queda localmente alojada la base de datos para que funcione      correctamente
  
Ejecucion del codigo

La reproduccion del codigo se encuentra en el notebook de jupyter llamado Proyecto Final Ciencia de datos.ipynb el cual en cada linea se especifica el codigo a ejecutar.



Resultados y conclusiones 

La informacion sobre conclusiones, finalidad y resultado se encuentran en el notebook de jupyter llamado Resultados y conclusiones.ipynb