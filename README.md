# IA2.2-LDA-y-Arboles-de-decision
Actividad del curso de Inteligencia Artificial I de los temas LDA y Arboles de decision

## Descripción
En esta actividad, se utiliza la base de datos que se trabajó en el primer parcial para generar un modelo de LDA y otro de árbol de decisión para compararlos en cuestión de rendimiento y de calidad y determinar cual es el mejor para el proyecto. La base de datos contiene información sobre datos históricos meteorológicos del área metropolitana de Monterrey así como de los niveles de partículas de PM2.5 en los diferentes días del año. Al estar compuesta de dos archivos diferentes se tuvo que hacer un merge entre bases de datos y se hizo un preprocesamiento previo. Los valores de las variables que se tienen son los siguientes:

- **Fecha**: Día del año en que se realizaron las mediciones meteorológicas y de contaminantes.
- **PM2.5 (ug/m³)**: Nivel registrado de partículas contaminantes PM2.5.
- **tavg**: Temperatura promedio calculada en grados celsius.
- **prcp**: Nivel de precipitación.
- **wdir**: Dirección del viento en medida de ángulo de 360 grados.
- **wspd**: Velocidad del viento.
- **pres**: Presión atmosférica.
- **tavg_pres**: Interacción entre temperatura promedio y presión atmosférica.
- **tavg_wspd**: Interacción entre temperatura promedio y velocidad del viento.
- **prcp_pres**: Interacción enre el nivel de precipitación y presión atmosférica.
  
En el proyecto parcial, se trata de predecir el nivel de PM2.5 en base a diferentes variables meteorológicas. En esta actividad se tratará de hacer algo similar, solo que a través de los modelos mencionados anteriormente, clasificando los registros de los niveles de PM2.5 en dos clases: "Niveles altos" y "Niveles bajos", tomando la mediana de los datos como punto de referencia para hacer la división y la binarización de los datos.

## Indice
Dentro de esta entrega se incluyen los siguientes archivos:
- [Reporte en html](./A2_2_531712.html)
- [Reporte en ipynb](./A2_2_531712.ipynb)
- [Base de datos](./MeteoContDB.csv)
