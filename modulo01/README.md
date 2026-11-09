# __Sesión 1__ Preparación de datos y análisis exploratorio (EDA)

>## Temas:
>    - Estadística descriptiva: media, varianza, asimetría y curtosis.
>    - Análisis univariado y bivariado: histogramas, boxplots, covarianza, correlación de Pearson y Spearman.
>    - Valores atípicos con boxplots y la regla del IQR; topes (censura) y transformaciones.
>    - Matriz de correlación, heatmaps y multicolinealidad.
>

 **Actividad:** identificar valores atípicos con boxplots y la regla del IQR, y hacer un EDA completo del conjunto California Housing. Trabajo individual, 40–50 minutos. El notebook descarga los datos al ejecutarse (requiere conexión a internet).



# __Sesión 2__ Preprocesamiento de datos
>## Temas:
> - Valores faltantes: mecanismos (MCAR, MAR, MNAR), borrar o imputar (media, mediana, KNN, iterativa).
> - Variables categóricas: codificación entera, ordinal y one-hot.
> - Escalado: StandardScaler, MinMaxScaler y RobustScaler.
> - División entrenamiento / validación / prueba, validación cruzada y fuga de datos.
> - Pipeline y ColumnTransformer de scikit-learn.
>

 **Actividad:** construir un pipeline de preprocesamiento sobre California Housing (faltantes, codificación, escalado, fuga de datos, Pipeline y ColumnTransformer). Trabajo individual, 60–75 minutos. El notebook descarga los datos al ejecutarse (requiere conexión a internet).

# __Sesión 3__ Ingeniería y selección de variables
>## Temas:
> - Creación de variables a partir del dominio: razones, transformaciones, interacciones y variables polinomiales.
> - Métodos de filtro: umbral de varianza, correlación e información mutua.
> - Métodos de envoltura: eliminación recursiva de variables (RFE).
> - Métodos integrados: selección basada en Lasso.
> - Comparación de métodos, estabilidad de la selección y fuga de datos al seleccionar.

 **Actividad:** Actividad: comparar métodos de selección de variables (filtro, RFE y Lasso) en un conjunto de datos médico (cáncer de mama de Wisconsin), con la selección dentro del Pipeline. Trabajo individual, 60–75 minutos. Los datos vienen incluidos en scikit-learn: no se necesita conexión a internet.
