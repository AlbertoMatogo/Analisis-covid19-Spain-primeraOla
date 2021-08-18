# Ciencia de datos aplicado al estudio de los datos del covid-19 en España (Primera ola)
## Este proyecto consta de 5 notebooks, cuyo objetivo es:
**visualización de los datos de las comunidades autónomas**

En el se pretende estudiar cómo ha afectado la evolución de la pandemia en las diferentes comunidades autónomas. Se calcula la incidencia acumulada por cada 100.000 habitantes en un periodo de 7 días. 
Se estudia el efecto de las siguientes variables en la evolución de los datos de la pandemia:
- Densidad de población
- Edad Media de la población
- Edad Mediana de la población
- Porcentaje de población con 65 años o más
- Efecto del índice de envejecimiento en la población

**Visualización de la evolución de los datos en España y Comparación de dicha evolución con los paises de Portugal, Italia y Alemania**
- Se procede con el análisis de la anomalia del número de fallecidos reflejado en MOMO
- Evolución de la incidencia acumulada
- Efecto de las decisiones en la evolución de los datos
- Efecto de la densidad en la incidencia acumulada en los 4 paises
- Efecto de la edad media en la incidencia acumulada media en los 4 paises
- Influencia de la población con 65 años o más en la incidencia acumulada, en los 4 paises
- Efecto de la población con edades comprendidas entre 15 y 65 años
- Efecto del porcentaje de población con 65 años o más vacunada
- Efecto conjunto población de entre densidad de población, población con 65 años o más
- Efecto conjunto de la densidad de población, y la población con 65 años o más en la IA acumulada
- Influencia conjunta de la población con edad entre 15 y 65 años, y el porcentaje de población vacunada sobre la IA
- Efecto del número de enfermer@s en la incidencia acumulada en defunciones
- Efecto de la influencia del nº de médicos (H/M) en la incidencia acumulada en defunciones
- Influencia de la población entre 15 y 65 años en la incidencia acumulada en defunciones
- Influencia de la población con 65 años o más en la incidencia acumulada en defunciones
- Influencia del nº de camas de UCI en la incidencia acumulada en defunciones
- Influencia del nº de camas de UCI y el nº de enfermeros, en la incidencia acumulada en defunciones

**Aplicación de modelos de regresión para los datos de España para categorizar según su importancia a la variable 'toma de decisiones'**
- Modelo de regresión lineal simple, aplicado sobre los datos de España
- Modelo polinómico simple, aplicado sobre los datos de España
- Modelo de crecimiento logístivo, aplicado sobre los datos de España
- Modelo de regresión lineal multivariable, aplicado sobre los datos de España

**Aplicación del modelo de crecimiento logístico a los datos de españa**
Se aplica el modelo de crecimiento logístico para obtener valores caracterísitcos del modelo, que son de utilidad para la simulación en el modelo SIR. Además de ampliar la información de como actua la enfermedad en una población con recursos limitados.

**Cálculo de R0, para la simulación de la evolución de los datos en entornos estáticos**
Se utiliza el modelo SIR, para simular la evolución de los datos de la pandemia en condiciones estáticas del entorno

**Control dinámico de la evolición de los datos, con Rt**
Se utiliza el cálculo de Rt para  llevar a cabo el control dinámico de la evolución de los datos dia a dia en condiciones cambiantes del entorno


####Fuentes Principales
                    
> "Europe dataset:", [Link](https://github.com/CSSEGISandData/COVID-19)。
> "datos_Comunidad_autonoma dataset:", [Link](https://cnecovid.isciii.es/covid19/)。
> "Momo_CCAA_2018_2020 dataset:", [Link](https://momo.isciii.es/public/momo/dashboard/momo_dashboard.html)。
> "Decisions made by the countries:", [Link](https://www.covid19healthsystem.org/searchandcompare.aspx)。
