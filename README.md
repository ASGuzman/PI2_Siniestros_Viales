# Análisis de Homicidios por Siniestros Viales en la Ciudad Autónoma de Buenos Aires, Argentina

## Introducción

En este proyecto, simulamos el rol de un Data Analyst en el equipo de analistas de datos de una empresa consultora que trabaja para el Observatorio de Movilidad y Seguridad Vial (OMSV) bajo la Secretaría de Transporte del Gobierno de la Ciudad Autónoma de Buenos Aires (CABA). Se nos encomendó la tarea de realizar un análisis de datos sobre homicidios en siniestros viales ocurridos en CABA entre 2016 y 2021.

El objetivo principal es proporcionar información que permita a las autoridades locales tomar medidas para reducir la cantidad de víctimas fatales en accidentes de tráfico. Se presentará un informe detallado de las tareas realizadas, las metodologías adoptadas y las conclusiones clave. Además, se desarrollará un dashboard interactivo para facilitar la interpretación de los datos y su análisis.

## Contexto

Los siniestros viales son una preocupación importante en la Ciudad Autónoma de Buenos Aires debido al alto volumen de tráfico y la densidad poblacional. La población de CABA corroborada en el ultimo censo realizado (2022) es de 3,120,612 habitantes en una superficie de 200 km².

## Datos

Se trabajó con la Base de Víctimas Fatales en Siniestros Viales en formato Excel, que contiene dos pestañas de datos: "HECHOS" y "VICTIMAS". Estas incluyen información sobre los eventos, víctimas, edad, sexo, modo de desplazamiento, etc. El análisis se basó en la exploración y limpieza de datos utilizando Python y Pandas.

## Tecnologías Utilizadas

Python y Pandas se emplearon para la extracción, transformación y carga (ETL) de datos, así como para el análisis exploratorio de datos (EDA). Se utilizó BeautifulSoup para el web scraping con el fin de obtener datos adicionales sobre la población en 2021. Para la construcción del dashboard interactivo, se optó por Power BI.

## ETL y EDA

Se realizó un exhaustivo proceso ETL para estandarizar nombres de variables, analizar nulos y duplicados, y eliminar columnas redundantes. Posteriormente, se llevó a cabo un análisis exploratorio para identificar patrones y tendencias que ayuden a tomar medidas preventivas.

## Análisis de los Datos

Se examinaron variables temporales, espaciales y características de las víctimas. Se destacaron patrones como la distribución mensual y semanal de los accidentes, el perfil de las víctimas (edad, sexo, modo de desplazamiento) y la distribución espacial de los hechos.

## KPI (Indicadores Clave de Rendimiento)

En función del análisis, se propusieron tres KPI con objetivos específicos para reducir la cantidad de víctimas fatales:

1. **Tasa de Homicidios en Siniestros Viales:** Reducir en un 10% la tasa en los últimos seis meses comparada con el semestre anterior.

2. **Accidentes Mortales de Motociclistas:** Disminuir en un 7% la cantidad en el último año respecto al año anterior.


## Conclusiones y Recomendaciones

Entre 2016 y 2021, se registraron 709 víctimas fatales en siniestros viales. Se presentaron recomendaciones, como continuar monitoreando los objetivos con campañas específicas, reforzar la seguridad vial en días específicos y dirigir campañas hacia grupos específicos, como conductores de motos y usuarios de avenidas. La evaluación de los KPI mostró éxito en la reducción de la tasa de homicidios en siniestros viales, pero no se cumplieron los objetivos en accidentes de motociclistas y avenidas para 2021. Se sugieren medidas adicionales y seguimiento continuo para mejorar la seguridad vial.

