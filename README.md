# Extraer-de-CSV-TSV-multiples-archivos-a-TXT
Extractor Que permite extraer de un CSV o TSV información de una columna específica de cientos de archivos a un TXT.

Resuelve la siguiente Problematica:

Tengo 365 archivos .tsv y me gustaría extraer solo la columna C del documento y guardarlos en un documento .txt El problema es que Podríamos realizarlo con Excel, pero muchas de las veces manejamos CSV o TSV con un tamaño enorme que hace que Excel no lea toda la información o simplemente se congele y se cierre. Con Power BI pasa exactamente lo mismo, al importar solo las columnas que necesitamos solo lee hasta 120 archivos, pero al leerlos demora más del tiempo y simplemente no responde.

El código Python es simple, ya que busca todos los archivos en la carpeta IMPUT y ejecuta la extracción de la columna deseada a un documento .txt en la carpeta OUTPUT. Solo deben configurar el siguiente parámetro:

.... usecols=['nombre de columna a extraer']))



