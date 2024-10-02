# Proyecto: Análisis de Telecomunicaciones en Argentina

Este es un proyecto situado en el rol de un Data Analyst. Se trata de un análisis completo que permita reconocer el comportamiento del sector de las telecomunicaciones a nivel nacional para Argentina. 

## Índice

1. [Introducción](#introducción)
2. [Descripción del Problema](#descripción-del-problema)
3. [Procesos Implementados](#procesos-implementados)
   1. [Extracción de Datos (ETL)](#extracción-de-datos-etl)
   2. [Análisis Exploratorio de Datos (EDA)](#análisis-exploratorio-de-datos-eda)
4. [Resultados Obtenidos](#resultados-obtenidos)
   1. [Análisis de Ingresos por Trimestre](#análisis-de-ingresos-por-trimestre)
   2. [Distribución de Conectividad por Tecnología](#distribución-de-conectividad-por-tecnología)
   3. [Análisis de Telefonía Móvil](#análisis-de-telefonía-móvil)
5. [Conclusiones y Recomendaciones](#conclusiones-y-recomendaciones)
6. [Fuente de los Datos](#fuente-de-los-datos)
7. [Contacto](#contacto)

## Introducción

Este proyecto tiene como objetivo realizar un análisis detallado del sector de telecomunicaciones en Argentina. El enfoque principal es identificar patrones en la conectividad de Internet y el comportamiento de los ingresos generados por los servicios de telecomunicaciones a lo largo de los últimos años, además de proporcionar recomendaciones para mejorar la calidad de los servicios y explorar oportunidades de crecimiento.

## Descripción del Problema

El problema radica en analizar el comportamiento del sector de telecomunicaciones en Argentina, enfocado principalmente en el acceso a Internet, pero también evaluando otros servicios de comunicación, con el fin de que la empresa prestadora de servicios de telecomunicaciones pueda identificar oportunidades de mejora y plantear soluciones personalizadas para sus clientes.

## Procesos Implementados

### Extracción de Datos (ETL)

El proceso ETL se aplicó a tres bases de datos principales: Internet, Mapa de Conectividad y Telefonía Móvil. Estos datasets fueron procesados para eliminar duplicados, valores faltantes y atípicos, y para transformar los datos en formatos adecuados para su análisis posterior.

### Análisis Exploratorio de Datos (EDA)

El análisis exploratorio fue realizado con los tres conjuntos de datos mencionados, donde se evaluaron las características generales de los datos, así como las principales tendencias y patrones.

1. **EDA Internet**: Se analizó la penetración de Internet en los hogares de Argentina, identificando cómo ha variado a lo largo del tiempo y su comportamiento por provincias.
2. **EDA Mapa de Conectividad**: Se estudió la distribución de las distintas tecnologías de acceso a Internet, como ADSL, fibra óptica, y telefonía fija.
3. **EDA Telefonía Móvil**: Se evaluaron los accesos a servicios de telefonía móvil, tanto en modalidad prepago como pospago, además de analizar los minutos salientes en estas categorías.

## Resultados Obtenidos

### Análisis de Ingresos por Trimestre

El análisis de ingresos reveló que el **primer trimestre** es el que genera los mayores ingresos promedio, superando los 50 millones de pesos. Este comportamiento puede estar relacionado con la alta demanda de servicios de Internet después de las festividades de fin de año.

El **segundo trimestre** mostró una caída significativa en los ingresos, mientras que en el **tercer** y **cuarto trimestre** se observó una leve recuperación, especialmente debido al regreso a clases y a las festividades de fin de año.

### Distribución de Conectividad por Tecnología

Se analizó la distribución de tecnologías de acceso a Internet en las distintas provincias. **Wireless** y **4G** fueron las tecnologías más frecuentes, con mayor número de accesos en la mayoría de las regiones. Provincias como Buenos Aires y Córdoba tienen un mayor número de accesos, mientras que otras provincias muestran una menor penetración tecnológica.

### Análisis de Telefonía Móvil

El análisis de telefonía móvil reveló un comportamiento interesante en los accesos prepago y pospago. Los servicios prepago mantienen una tendencia estable, mientras que los accesos pospago muestran un leve aumento en los últimos años. Sin embargo, los **minutos salientes** han disminuido significativamente en ambas categorías, lo cual puede estar vinculado al crecimiento del uso de aplicaciones de mensajería en lugar de llamadas tradicionales.

## Conclusiones y Recomendaciones

A partir de los análisis realizados, se pueden identificar varias áreas de mejora y recomendaciones para la empresa:

1. **Mejorar la infraestructura de conectividad en provincias menos desarrolladas**: Las provincias con menor número de accesos tecnológicos (como La Pampa o Formosa) podrían beneficiarse de una mejora en la infraestructura, especialmente en el despliegue de tecnologías como fibra óptica.
   
2. **Implementar planes de fidelización**: Dado que los accesos pospago muestran una tendencia creciente, sería recomendable ofrecer mejores planes de fidelización a los clientes que utilizan esta modalidad, incentivando su permanencia y aumentando la cuota de mercado.

3. **Diversificar los servicios en los trimestres bajos**: El segundo trimestre muestra una caída significativa en los ingresos. La empresa podría implementar estrategias de marketing y promociones para captar nuevos clientes o aumentar la demanda de servicios durante este período.

4. **Adaptar la oferta a los cambios de comportamiento de consumo**: Dado que los minutos salientes han disminuido, se recomienda evaluar la posibilidad de adaptar los paquetes de telefonía móvil para incluir más servicios de datos en lugar de minutos de llamadas, respondiendo a la creciente demanda de aplicaciones de mensajería.

Estas acciones permitirán a la empresa mejorar la calidad del servicio, satisfacer mejor las necesidades de los clientes, y aprovechar las oportunidades de crecimiento en el sector.

## Fuente de los Datos

Los datos utilizados en este análisis fueron obtenidos de la página de **Datos Abiertos de ENACOM** (Ente Nacional de Comunicaciones de Argentina). Se utilizaron tres datasets principales:

1. **[Internet](#)**: Información sobre la penetración del servicio de Internet en Argentina.
2. **[Mapa de Conectividad](#)**: Datos sobre las tecnologías de acceso a Internet distribuidas por provincias.
3. **[Telefonía Móvil](#)**: Información sobre los accesos y minutos de telefonía móvil en modalidad prepago y pospago.

Estos datasets abarcan el período comprendido entre el año 2014 y el primer trimestre de 2024.

---

# Contacto

Para obtener más información o realizar preguntas sobre el proyecto, puedes ponerte en contacto con el autor:

Nombre: Jose Yesid Cruz

Correo Electrónico: jose-1941@hotmail.com

LinkedIn: [https://www.linkedin.com/in/jose-yesid-cruz-pinto-a25b91127/](https://www.linkedin.com/in/jose-yesid-cruz-pinto-a25b91127/)
