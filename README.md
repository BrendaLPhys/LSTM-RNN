## Proyecto red neuronal RNN

**Objetivo:** Que el estudiante practique el entrenamiento de una red neuronal tipo RNN (Recursive Neural Network) con la finalidad de entrenar un modelo que permita hacer una predicción en base a datos ordenados de manera secuencial (series temporales)

El proyecto debe tener los siguientes elementos: 

  1.	Selección de datos secuenciales:  Los datos pueden ser seleccionados de un repositorio como kaggle, para ser usados en una red LSTM deben estar ordenados temporalmente (ejemplo:  stock market, temperatura, trafico, frecuencia cardiaca, etc....)

  2.	Procesamiento de datos: Cargar los datos y ordenarlos en bloques temporales para ser utilizados en una red LSTM

  3.	Red neuronal: Definir la arquitectura y los parámetros de una red neuronal LSTM para entrenar el modelo (configuración inicial)

  4.	A partir de los resultados de la configuración inicial y si se observa “overfitting” aplicar el método de “Dropout” 

  5.	Explorar las siguientes variaciones a la red neuronal para investigar si se pueden mejorar los resultados: 

      a.	Variación 1:  Cambiar la configuración de la red neuronal de una LSTM normal a Bidireccional y Stacked 

      b.	Variación 2:  Una variación del optimizer 

      c.	Variación 3: Cambiar el batch_size (ejemplo de 32 a 64)
      

  6.	presentación de resultados: Se deben de presentar los gráficos obtenidos para la configuración inicial y para cada variación propuesta, comparación de la secuencia temporal con el modelo entrenado

  7.	Conclusiones:  En base a los resultados discutir si fue exitoso el entrenamiento  

# Erupciones Solares

Las condiciones dinámicas y eventos en el sol en el espacio cercano a la Tierra y en la parte alta de la atmósfera juegan un papel importante tanto en las vidas humanas como en la tecnología. Estos fenómenos son descritos por el clima espacial. La actividad solar da lugar a variedad de climas espaciales. La actividad solar consiste en erupciones solares,  eyecciones de masa coronal o CME (por sus siglas en inglés: Coronal Mass Ejection), viento solar de alta velocidad, y partículas energéticas solares. El campo solar magnético es la principal fuente de esta actividad. **[1]**

Las erupciones solares son erupciones energéticas de radiación electromagnética del sol con una duración de entre sólo unos minutos hasta horas. Los impactos terrestres de erupciones pequeñas son limitados, pero erupciones fuertes tienen efectos significativos en la atmósfera. El aumento en la ionización afecto la cantidad de electrones, que a su vez afecta la transmisión de ondas de radio y la exactitud de sistemas de posicionamiento globales. El calentamiento ionosférico hace que se expanda la atmósfera, aumentando la densidad de la tierra y el arrastre de satélites, alterando sus órbitas. Erupciones fuertes están comunmente acompañadas de eyecciones de masa coronal o CMEs que causan un impacto considerable en el medio ambiente de la Tierra. Por lo tanto, vale la pena mejorar la predicción de erupciones solares, especialmente las de mayor intensidad. **[2]**

Los datos utilizados provienen del producto llamado Spaceweather HMI Active Region Patches, producido por el equipo SDO/HMI. Estos datos fueron liberados a finales de 2012 y pueden ser encontrados como la serie de datos hmi.sharp en el *Joint Science Operations Center (JSOC)*. Los datos de SHARP comprenden regiones activas automáticamente identificadas y rastreadas en mapas y proporcionan una buena cantidad de parámetros físicos útiles para la detección de erupciones. **[3]**

**Referencias y fuentes de consulta:**

* Artículo 1 - [Forecasting Space Weather Using Deep Learning
Techniques **(2018)**](https://scholarworks.utep.edu/cgi/viewcontent.cgi?article=1055&context=open_etd)

* Artículo 2 - [Predicting Solar Flares with Machine Learning: Investigating Solar Cycle Dependence **(2020)**](https://iopscience.iop.org/article/10.3847/1538-4357/ab89ac/pdf)

* Artículo 3 - [Predicting Solar Flares Using a Long Short-term Memory Network **(2019)**](https://iopscience.iop.org/article/10.3847/1538-4357/ab1b3c/pdf)

* [Repositorio de Artículo 3 y fuente de los datos](https://github.com/JasonTLWang/LSTM-flare-prediction)

## **TOTUSJH** = Total unsigned current helicity 

*Total unsigned magnetic helicity for flaring active regions shows an increasing trend before the first flare and the active region starts the flaring activity when the value of magnetic helicity is sufficiently high. [source](https://arxiv.org/pdf/2003.03878.pdf)*
