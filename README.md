# <h1 align=center> **SINIESTROS VIALES**  </h1>
<p align="center">

![siniestro](img\siniestro.jpeg)

## Introducción 
Por parte del equipo de analistas de datos de una empresa consultora a la cual el Observatorio de Movilidad y Seguridad Vial (OMSV), que es un centro de estudios que se encuentra bajo la órbita de la Secretaría de Transporte del Gobierno de la Ciudad Autónoma de Buenos Aires (CABA), se solicitó la elaboración de un proyecto de análisis de datos.

El fin de este proyecto es generar información que le permita a las autoridades locales tomar medidas para disminuir la cantidad de víctimas fatales de los siniestros viales ocurridos en CABA. Para ello, se pone a disposición un dataset sobre homicidios en siniestros viales acaecidos en la Ciudad de Buenos Aires durante el periodo 2016-2021.

Se espera como productos finales un reporte de las tareas realizadas, metodologías adoptadas y principales conclusiones y la presentación de un dashboard interactivo que facilite la interpretación de la información y su análisis.


## Contexto

Los siniestros viales, también conocidos como accidentes de tráfico, son eventos que involucran vehículos en vías públicas y pueden tener diversas causas y consecuencias, desde daños materiales hasta lesiones graves o fatales. En la Ciudad Autónoma de Buenos Aires, con una población de 3,121,707 habitantes y 1,616,327 vehículos registrados en noviembre de 2023, la prevención de siniestros viales es crucial para la seguridad de sus residentes y visitantes.


## Datos Utilizados

Para este proyecto se utilizó la Base de Víctimas Fatales en Siniestros Viales, en formato Excel, que contiene dos pestañas de datos:

- **HECHOS**: una fila por hecho con un id único y variables temporales, espaciales y de participantes.
- **VICTIMAS**: una fila por víctima, con variables de edad, sexo y modo de desplazamiento, vinculada a los HECHOS por el id del hecho.


## Tecnologíaas Utilizadas

- **Python / Pandas **
- **Power BI **


## ETL y EDA

 **EDA**: Se realizó un análisis exhaustivo para encontrar patrones que permitan generar información útil para las autoridades locales. Se realizaron las misma consulta pero en dos diversos archivos:

 *** EDA_bruto ***: Se realizo un análisis de los datos en bruto para recolectar informacion util para el proceso de Transformacion de los datos [EDA_bruto](EDA_bruto).

 *** EDA ***: Se realizo el mismo proceso de análisis pero ya con los datos procesados [EDA](EDA).

 **ETL**: Se estandarizaron nombres de variables, se analizaron nulos y duplicados, y se eliminaron columnas redundantes [ETL](ETL).


## KPIs

1. **Reducir en un 10% la Tasa de Homicidios en Siniestros Viales en los últimos seis meses en comparación con el semestre anterior**:

Definimos a la tasa de homicidios en siniestros viales como el número de víctimas fatales en accidentes de tránsito por cada 100.000 habitantes en un área geográfica durante un período de tiempo específico.

2. **Reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año respecto al año anterior**:

Definimos a la cantidad de accidentes mortales de motociclistas en siniestros viales como el número absoluto de accidentes fatales en los que estuvieron involucradas víctimas que viajaban en moto en un determinado periodo temporal.


## Conclusiones y Recomendaciones

Entre 2016 y 2021, se registraron 717 víctimas fatales. El análisis revela que:
- El 70% de las víctimas fallecieron durante la semana, especialmente entre las 6 y 8 de la mañana durante el fin de semana.
- Diciembre tuvo el máximo de fallecimientos.
- El 77% de las víctimas eran masculinas, con casi el 50% entre 25 y 44 años.
- El 42% de las víctimas eran motociclistas.
- El 62% de los homicidios ocurrieron en avenidas, siendo el 82% en cruces.


### Recomendaciones

1. Continuar monitoreando los objetivos y realizar campañas puntuales, especialmente para conductores de motos y usuarios de avenidas.
2. Reforzar las campañas de seguridad vial entre viernes y lunes, con especial énfasis en diciembre.
3. Implementar campañas de conducción segura en avenidas y cruces de calles.
4. Dirigir campañas de seguridad hacia los hombres, especialmente en relación con la conducción de motos.
