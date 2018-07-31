# Descripción
Genera secuencias de datos y las almacena en ficheros de una carpeta definida.

# Prerequisitos
Tener instalada la Maquina virtual HortonWorks DataFlow

# Definición de carpeta de salida
Se debe crear un directorio con permisos donde almacenar <br>
mkdir nifi_examples<br>
chmod 777 nifi_examples<br>
cd nifi_examples<br>
mkdir in<br>
mkdir out<br>
chmod 777 in<br>
chmod 777 out<br>
cd in<br>
vi personas.csv<br>
<br>
Incluir el siguiente contenido en el fichero personas.csv<br>
<br>
nombre, edad, salario<br>
Pedro, 24, 21000<br>
Maria, 26, 24000<br>
Juan, 28, 25000<br>
Luis, 35, 28000<br>
Monica, 42, 30000<br>
Rosa, 43, 25000<br>
Susana, 45, 39000<br>


# Importar el Flujo de datos
El flujo de datos se puede descargar del fichero XML: csv_to_json.xml
