# Logical backup y physical backup con MySQLWorkbench

LOGICAL BACKUP CON MYSQL WORKBENCH

1. Abrir MySQL Workbench.
2. Conectarse al servidor MySQL.
3. Ir a: Server → Data Export.
4. Seleccionar la base de datos.
5. Marcar: Export to Self-Contained File.
6. Elegir la ruta del archivo, por ejemplo:
   C:\MyBackups
7. Marcar las opciones:
   - Dump Structure and Data
   - Include Create Schema
8. Clic en: Start Export.

Resultado:
Se generará un archivo .sql con tu respaldo lógico.

PHYSICAL BACKUP CON MYSQL WORKBENCH

1. Abrir MySQL Workbench.
2. Conectarse al servidor MySQL.
3. Seleccionar la base de datos que se quiere hacer backup.
4. Click derecho en la tabla que se desea hacer el backup.
5. Seleccionar Table Data Export Wizard.
6. Seleccionar las tablas y columnas.
7. Elegir el formato para el backup csv o json
8. 6. Elegir la ruta del archivo, por ejemplo:
   C:\MyBackups
9. Dar en siguiente hasta finalizar
10. Se debe haber generado un archivo csv o json en la ruta seleccionada.
