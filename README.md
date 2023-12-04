# Análisis de Homicidios por Siniestros Viales en la Ciudad Autónoma de Buenos Aires, Argentina

## Introducción

En este proyecto, simulamos el rol de un Data Analyst en el equipo de analistas de datos de una empresa consultora que trabaja para el Observatorio de Movilidad y Seguridad Vial (OMSV) bajo la Secretaría de Transporte del Gobierno de la Ciudad Autónoma de Buenos Aires (CABA). Se nos encomendó la tarea de realizar un análisis de datos sobre homicidios en siniestros viales ocurridos en CABA entre 2016 y 2021.

El objetivo principal es proporcionar información que permita a las autoridades locales tomar medidas para reducir la cantidad de víctimas fatales en accidentes de tráfico. Se presentará un informe detallado de las tareas realizadas, las metodologías adoptadas y las conclusiones clave. Además, se desarrollará un dashboard interactivo para facilitar la interpretación de los datos y su análisis.

## Contexto
Los percances viales, también denominados incidentes de tráfico, siniestros viales o accidentes de tránsito, representan situaciones donde vehículos se ven involucrados en espacios públicos. Estos eventos pueden ser desencadenados por diversas causas, como colisiones entre automóviles, motocicletas, bicicletas o peatones, atropellos, impactos contra objetos fijos o incluso caídas de vehículos. Las consecuencias abarcan desde daños materiales hasta lesiones graves o, lamentablemente, pérdidas fatales para los afectados.
Los siniestros viales son una preocupación importante en la Ciudad Autónoma de Buenos Aires debido al alto volumen de tráfico y la densidad poblacional. La población de CABA corroborada en el ultimo censo realizado (2022) es de 3,120,612 habitantes en una superficie de 200 km².

## Datos

Se trabajó con la Base de Víctimas Fatales en Siniestros Viales en formato Excel, que contiene dos pestañas de datos: "HECHOS" y "VICTIMAS". Estas incluyen información sobre los eventos, víctimas, edad, sexo, modo de desplazamiento, etc. El análisis se basó en la exploración y limpieza de datos utilizando Python y Pandas.

## Tecnologías Utilizadas

Python y Pandas se emplearon para la extracción, transformación y carga (ETL) de datos. Para el análisis exploratorio de datos (EDA) se utilizaron librerias como Seaborn, Matplotlib, numpy y pandas. Por ultimo para lo que represento la creacion del dashboard se utilizo PowerBi

## Proceso de trabajo

### ETL y EDA

Se realizó un exhaustivo proceso ETL para estandarizar nombres de variables, analizar nulos y duplicados, y eliminar columnas redundantes. Posteriormente, se llevó a cabo un análisis exploratorio para identificar patrones y tendencias que ayuden a tomar medidas preventivas.

### Análisis de los Datos

El análisis integral de los datos sobre siniestros viales en la Ciudad Autónoma de Buenos Aires (CABA) revela patrones y tendencias significativas:

**Datos Generales:**
- El conjunto de datos cuenta con 707 registros y 25 columnas, proporcionando información detallada sobre accidentes, víctimas, ubicación y detalles temporales.

**Características Temporales:**
- Los accidentes parecen distribuirse de manera relativamente uniforme a lo largo de los años, meses y días, con un promedio de 1.06 víctimas por incidente.

**Ubicación y Franja Horaria:**
- La mayoría de los accidentes ocurren en las franjas horarias de 6:00 a 12:00 y de 18:00 a 24:00 horas, y la Comuna 1 es la más afectada.
- Las avenidas son escenarios comunes de accidentes, representando el 62% de las víctimas, con un pico los sabados.

**Edad:**
- La edad promedio de las víctimas es de aproximadamente 42 años.
- La mayoría de las víctimas tienen edades comprendidas entre 20 y 40 años, destacando la importancia de dirigir estrategias de seguridad vial a este grupo.

**Género:**
- El 76.6% de las víctimas son masculinas, siendo este género predominante en todos los roles, ya sea conductor, pasajero o peatón.

**Roles y Responsabilidad:**
- El 48% de las víctimas desempeñaba el rol de conductor, principalmente en motos.
- Los conductores de automóviles, colectivos y camiones son responsables del 75% de los casos donde se señala un vehículo como responsable.

**Distribución Espacial:**
- Las avenidas son puntos comunes de accidentes en todas las comunas, siendo los cruces con otras calles el escenario más frecuente (82% de los casos).

**Patrones Temporales:**
- Se observa un aumento en la cantidad de accidentes en diciembre, posiblemente relacionado con la flexibilización de las medidas de cuarentena.
- A nivel mensual, la distribución varía, con picos de accidentes en diferentes meses en distintos años.

**Relación entre Víctimas y Acusados:**
- Las motos son frecuentes víctimas pero raramente acusadas. Los autos, por otro lado, son comunes en ambos roles.

**Conclusiones Generales:**
- Las comunas 1, 4, 9 y 8 tienen un mayor riesgo de accidentes, posiblemente debido a una alta densidad de población y tráfico vehicular.
- Aunque la edad promedio de las víctimas es alrededor de los 42 años, se destaca la importancia de centrar esfuerzos en la seguridad vial de los jóvenes de 20 a 40 años.
- La distribución de incidentes a lo largo del año y la semana muestra patrones variados, destacando la necesidad de estrategias flexibles y adaptativas.
- Las avenidas, especialmente en cruces con otras calles, son puntos críticos que requieren atención específica en términos de seguridad vial.

Este análisis integral proporciona una visión completa de la problemática de los siniestros viales en la Ciudad Autónoma de Buenos Aires, ofreciendo insights valiosos para orientar acciones preventivas y mejorar la seguridad vial en la región.

### KPI (Indicadores Clave de Rendimiento)

En función del análisis, se propusieron tres KPI con objetivos específicos para reducir la cantidad de víctimas fatales:

1. **Tasa de Homicidios en Siniestros Viales:** Reducir en un 10% la tasa en los últimos seis meses comparada con el semestre anterior.

2. **Accidentes Mortales de Motociclistas:** Disminuir en un 7% la cantidad en el último año respecto al año anterior.


## Conclusiones y Recomendaciones

Entre 2016 y 2021, se registraron 709 víctimas fatales en siniestros viales. Se presentaron recomendaciones, como continuar monitoreando los objetivos con campañas específicas, reforzar la seguridad vial en días específicos y dirigir campañas hacia grupos específicos, como conductores de motos y usuarios de avenidas. La evaluación de los KPI mostró éxito en la reducción de la tasa de homicidios en siniestros viales, pero no se cumplieron los objetivos en accidentes de motociclistas y avenidas para 2021. Se sugieren medidas adicionales y seguimiento continuo para mejorar la seguridad vial.

