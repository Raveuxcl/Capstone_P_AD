Por hacer: Añadir markdowns explicativos del desarrollo del notebook (limpieza, manejo, adaptación de los ds, implementación de forecasting regresivo con variables exógenas, predicción etc)
- Incorporar algunas visualizaciones en el apartado de exploración de datos.
- Incorporar hipotesis y conclusiones ()
Extra (no obligatorios): validar modelo generando matriz de confusión o ejecutando una predicción con un ds inventado.

-------------------------------- PARA ENTREGA ---------------------------------

Integrantes:
- Javier Vega
- Vicente Gallardo

Este proyecto analiza el estado del servicio de antenas de servicio movil (UPTIME) en la Region Metropolitana y como se ve afectado el funcionamiento del servicio cuando existen precipitaciones, o bien cuando existen variaciones
en la temperatura. Este analisis se hizo con el analisis de varios data sets, especicifamente:

Uptime:
	- raw.uptime.20222.csv
		Data set obtenido obtenido de manera interna. Muestra el estado UPTIME del servicio movil diario.

Precipitaciones:
	- ElPaico_AguaCaída_2022.xls ; Eulogio_AguaCaída_2022.xls ; Pudahuel_AguaCaída2022.xls ; QuintaNormalAguaCaída_2022.xls ; SanJoseAguaCaída_2022.xls
		Data sets obtenidos de La Direccion Meterologica de Chile. Muestran informacion sobre la cantidad en mm de lluvia por dia en lo que va del ano 2022. Tambien existe mas informacion estadistica la cual no se utilizara para
		el desarrollo de este analisis.

Temperatura
	- TemperaturaMedi_2022_Pudahuel.xls ; TemperaturaMedia_2022_ElPaico.xls ; TemperaturaMedia_2022_Eulogio.xls ; TemperaturaMedia_2022_QuintaNormal.xls ; TemperaturaMedia_2022_SanJose.xls
		Data sets obtenidos de La Direccion Meterologica de Chile. Muestran informacion sobre la temperatura medua por dia en lo que va del ano 2022. Tambien existe mas informacion estadistica la cual no se utilizara para
		el desarrollo de este analisis.


Se utilizaron sensores de las comunas de El Paico, La Reina(Eulogio Sanchez), Pudahuel, Quinta Normal y San Jose, que tiene la Direccion Meteorologica de Chile.
Primero se trabajaron las bases por separados, reemplazando valores nulos y trabajando el formato de los datos. Luego se unieron las bases y se entreno un modelo Random Forest.

Para el recorrido de este proyecto es necesario leer el notebook de Jupyter Capstone Project.
