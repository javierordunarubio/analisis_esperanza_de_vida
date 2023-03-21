# Predicción de la esperanza de vida

**Lenguaje de programación empleado: R.**

En este repositorio se plantea un problema de predicción de la esperanza de vida en los diferentes países del mundo en base a una serie de variables, donde para abordarlo se utilizan una serie de modelos multilineales. El problema consta de dos partes: la primera parte consiste básicamente en un análisis exploratorio de los datos, para posteriormente pasar a realizar una serie de modelos multilineales empleando estos mismos datos. La segunda parte consiste en la realización de un análisis para buscar si existe una relación entre la esperanza de vida y el consumo de alcohol.

Los datos empleados provienen del repositorio de datos del Observatorio Mundial de la Salud de la OMS. En nuestro estudio sólo trabajaremos con el fichero completo del año 2014 (EV2014.RData) y los predictores del año 2015 (EV2015.RData). Las variables de estos datos son un conjunto de indicadores sociales y de salud de los diferentes países recogidos. Estas variables son:
*Country: Variable de texto, indicando el nombre del país
*Year: Constante igual a 2014 en la primera base, constante igual a 2015 en la segunda base.
*Life Expectancy: Esperanza de vida al nacer en años, ausente en la base para 2015.
*Status: Estatus de país en desarrollo (Developing) o desarrollado (Developed),
*Adult.Mortality: Tasa de mortalidad en adultos (15-65 años) por 1000 habitantes,
*infant.deaths: Número de defunciones infantiles por 1000 habitantes,
*Alcohol: Consumo de alcohol per cápita (mayores de 15 años), en litros de alcohol puro,
*percentage.expenditure: Gasto en salud per cápita, como porcentaje del producto interior bruto,
*Hepatitis.B: Cobertura en porcentaje de inmunización a la hepatitis B en menores de 1 año de edad,
*Measles: Número de casos reportados de sarampión por 1000 habitantes,
*BMI: IMC promedio en el país,
*under.five.deaths: Número de defunciones de menores de 5 años por 1000 habitantes,
*polio: Cobertura en porcentaje de inmunización a la poliomielitis en menores de 1 año de edad,
*Total.expenditure: Gasto general en salud, como porcentaje del gasto total gubernamental,
*Diphtheria: Cobertura en porcentaje de inmunización a la difteria, tétanos y DTP3 en menores de 1 año de edad,
*HIV.AIDS: Número de defunciones por HIV/Sida en menores de 5 años, por cada 1000 niños
nacidos vivos,
*GDP: Producto Interior Bruto en dólares americanos,
*Population: Número de habitantes,
*thinness..1.19.years: Prevalencia ( %) de delgadez extrema en niños/adolescentes entre 10 y 19 años,
*thinness.5.9.years: Prevalencia ( %) de delgadez extrema en niños entre 5 y 9 años.
*Income.composition.of.resources: Índice de desarrollo humano en términos de las fuentes de composición de los ingresos(entre 0 y 1)
*Schooling: Número medio de años de escolarización.




**El contenido de este repositorio está escrito exclusivamente en castellano. // The content of this repo is written exclusively in spanish.**
