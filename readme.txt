Integrantes:
- Javier Vega
- Vicente Gallardo

Este proyecto analiza el estado del servicio de antenas de servicio movil (UPTIME) en la Region Metropolitana y como se ve afectado cuando existen precipitaciones, o bien cuando existen variaciones
en la temperatura, para posteriormente utilizar estas variables y ejecutar un modelo de forecasting predictivo con base autoregresiva y variables exógenas. Durante el desarrollo se utilizan varios data sets, especicifamente:

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

Para el recorrido de este proyecto es necesario leer el notebook o archio html "Capstone Project".
