# ih_datamadpt1121_project_m3
Modelo de machine learning

Consistia en crear un modelo de machine learning que prediga los precios de diamantes. Para ello se ha analizado los distintos precios (target) y features (dividas en categoricas y numericas). 

Metodología: 
Importar librerías: Numpy, pandas, sklearn, sqlalchemy, pickle.
Acceder a la base de datos.db
Preparación de los datos: Diferenciar entre las features categoricas, númericas y definir el target
Get dummies: Las features categóricas se deben transformar en números para que pueda funcionar el modelo con el método get.dummies
Estandarizar las features
Dividir el modelo de entrenamiento (test) del de train.
Prueba de modelos: LinearRegression(), RandomForestRegressor()
