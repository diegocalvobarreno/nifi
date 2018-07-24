# Descripción
Genera secuencias de datos y las almacena en ficheros de una carpeta definida.

# Prerequisitos
Tener instalada la Maquina virtual HortonWorks DataFlow

# Definición de carpeta de salida
Se debe crear un directorio con permisos donde almacenar los datos generados
mkdir nifi_examples
chmod 777 nifi examples
cd nifi_examples
mkdir generator_to_file
chmod 777 generator_to_file

# Importar el fichero XML donde viene el código de la definición del flujo
Importar: generator_to_file.xml
