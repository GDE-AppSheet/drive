Script Simple para Crear Carpeta en Google Drive con Fecha de Creación
Este script permite la creación automática de una carpeta en Google Drive, incluyendo la fecha en su nombre.

Instrucciones de Uso
1. Requisitos Previos
Acceso a Google Drive.
El ID de la carpeta padre donde deseas crear la nueva carpeta.
2. Código del Script
Copia el siguiente código en Google Apps Script y reemplaza el valor de parentFolderId con el ID de tu carpeta padre.
Guarda el script y ejecútalo.
Se creará una carpeta con el nombre "Nueva Carpeta - dd-mm-yyyy" en la carpeta padre especificada.


Google Apps Script para Listar Archivos desde Google Cloud Storage y Guardarlos en Google Sheets
Este script permite listar archivos almacenados en un bucket de Google Cloud Storage (GCS) y registrar sus detalles (nombre, URL, extensión, tamaño, timestamp, metadatos) en una hoja de cálculo de Google Sheets. También utiliza un archivo JSON de una cuenta de servicio para obtener las credenciales necesarias.

Requisitos
1. Cuenta de Google Cloud
Bucket en Google Cloud Storage con los archivos que deseas listar.
Cuenta de servicio configurada en Google Cloud con acceso a los buckets de GCS.
Archivo JSON de la cuenta de servicio descargado para autenticar las solicitudes.
2. Google Drive
Subir el archivo JSON de la cuenta de servicio a Google Drive.
3. Google Sheets
Hoja de cálculo de Google Sheets donde se guardarán los detalles de los archivos listados desde GCS.
Instrucciones de Configuración
1. Subir el Archivo JSON de la Cuenta de Servicio
Descarga el archivo JSON de la cuenta de servicio de Google Cloud.
Sube el archivo JSON a tu Google Drive.
Copia el ID del archivo JSON desde Google Drive (lo encontrarás en la URL cuando el archivo esté abierto).
2. Crear una Hoja de Cálculo en Google Sheets
Crea una nueva hoja de cálculo en Google Sheets.
Copia el ID de la hoja de cálculo (lo encontrarás en la URL).
3. Configurar el Script
Abre Google Apps Script desde Google Drive o Google Sheets.
Crea un nuevo proyecto y copia el código proporcionado (ver la sección de Código más abajo).
Reemplaza los siguientes valores en el script:
ID del archivo JSON: Reemplaza 'PON_AQUI_EL_ID_DEL_ARCHIVO_JSON' con el ID del archivo JSON de tu cuenta de servicio subido a Google Drive.
Nombre del bucket de GCS: Reemplaza 'PON_AQUI_EL_NOMBRE_DE_TU_BUCKET' con el nombre de tu bucket de Google Cloud Storage.
ID de la hoja de cálculo: Reemplaza 'PON_AQUI_EL_ID_DE_LA_HOJA_DE_CALCULO' con el ID de la hoja de cálculo de Google Sheets donde se guardarán los datos.
