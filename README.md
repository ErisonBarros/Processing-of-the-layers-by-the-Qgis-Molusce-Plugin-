# Processing of the layers by the Qgis Molusce Plugin

From the exploratory analysis of the 2010 data, since they are the data but close to the reality of the last census we verify in a routine in python and R we study the distribution of variables and generate the correlation matrix of variables.


**Correlation matrix between the variables**


<img src="https://i.ibb.co/nR0V0hK/Correla-o.png" alt="Correla-o" border="0">

------------
## Uso do Solo em 2000, 2010 e 2018

<a href="https://ibb.co/wQLFkmK"><img src="https://i.ibb.co/QHc3gw6/Figure-4.png" alt="Figure-4" border="0"></a>


## USE OF MOLUSCE PLUGIN

We introduced the standardized and normalized raster of socioeconomic and infrastructure variables in Qgis. We started the processing.

**Input screen of the variables**
<img src="https://i.ibb.co/FbY6xR0/Variaveis-Utilizadas.png" alt="Variaveis-Utilizadas" border="0">

The correlations present in the data were verified in tabular form, it continued to exist in the form of raster data. In front of simulations we verified which variables would be more important to explain the irregular occupations on the BR-408 highway domain ranges.

**Correlation Matrix between standardized raster of socioeconomic variables.**
<img src="https://i.ibb.co/2dh94JM/correla-o-das-variaveis.png" alt="correla-o-das-variaveis" border="0">
The reclassified maps relating to the 2000 land use and occupation map (initial map) and the 2010 land use and occupation map (final map) were used to calculate the Transition Matrix (Table 03). The rates of change are obtained by calculating the transition matrix, which is the total amount of change for each type of land cover transition taking into account the time period of the simulation (time difference in years between 2000 and 2010) through a cross-tab operation.

<img src="https://i.ibb.co/h99DqhM/Tabela-de-varia-o-da-distribui-o-das-celulas.jpg" alt="Tabela-de-varia-o-da-distribui-o-das-celulas" border="0">


From this, we generate the transition matrix that seeks to explain how the transition between cells happens and their probabilities and statistics for each transition that occurs in the track in the period 2000 and 2010.

1. Forestry / Non-Forestry Natural Formation
2. Farming
3. Non-Vegetated Area
4. bodies of water
5. Irregular Occupation

**Modelof Trasition Potentials - Parameters of the Logistic Regression Model**
<img src="https://i.ibb.co/L08C7mv/resultados-Por-regress-o-logistica.png" alt="resultados-Por-regress-o-logistica" border="0">

------------
## Choice of Transition potential models

<img src="https://i.ibb.co/vkQ1S4V/Screenshot-39.png" alt="Screenshot-39" border="0">

They are the Models:
- Multi-layer Neural Network Perception (ANN)
- Logistic Regressio

The models that presented the best statistical results.

**Validação dos modelos de Potencial de transição**
<img src="https://i.ibb.co/XCxrdYq/Simula-o-Por-RN.png" alt="Simula-o-Por-RN" border="0">
**Parâmetros da Matriz Kappa para  Validação dos modelos de Potencial de transição**
<img src="https://i.ibb.co/LgjzZKq/Simula-o-Por-regress-o-logistica.png" alt="Simula-o-Por-regress-o-logistica" border="0">
