# Macro Mandatos

  La macro permite para crear archivos de tipo nominacoop para el sistema SIDEP a partir de datos tomados 
  de la tabla mandato 
  
# Requisitos
  
  Microsoft Excel

# Ejecucción
  
  Para la ejecución de esta macro se requiere:
  
  * Seleccionar de la tabla Mandatos de la base Previred_sidep, los registros requeridos
  
  * Se deben separar en columnas
  	
	Por el DBeaver:
	- Clck derecho sobre registros seleccionados, luego Export Resultset
	- Seleccionar CSV, luego click en Siguiente (3 veces)
	- Seleccionar 'Copy to Clipboard', Siguiente y Finalizar

	Por el SQL Server:
	- Copiar los registros requeridos
	  (los pegará automáticamente separados en columnas)
  
# Pasos

  * Abrir archivo macro PAGOSv3.xls ubicado en:
    \\172.25.71.29\Tecnologia\Proyectos en Testing\Certificaciones\SIDEP\TIPS\pruebas
	
  * Pegar los registros de mandatos (copiados previamente) en la hoja 'mandatos' a partir de la celda A2
    (Actualmente la hoja está configurada para recibir registros desde la fila 2 hasta la fila 31)
	
  * Activar la hoja 'Final' para ver resultado de la conversion de datos
  
  * El rango de celdas convertidas al formato de ancho fijo aparecerá seleccionado. Copiar y Pegar en un 
    archivo nuevo de texto. 
  
  * Guardar el archivo de texto creado con nomenclatura nominacoop 
    (ejemplo: nominacoop_01284_00001_012019_25.txt)
  
  
 # Notas
 
  * La hoja 'PAGOS' contiene estructura de Archivo Solicitud de Pagos
  
  * La hoja 'Tipo registro 1' contiene conversión inicial de los datos