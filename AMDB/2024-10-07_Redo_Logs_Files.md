---
date: 2024-10-07
tags:
    -
hubs:
     "[[AMDB_HUB]]"
urls:
    -
---

# Redo_Logs_Files

## Recovery Manager(RMAN)

* Datafiles y Controlfiles
* Archivo de parámetros del servidor
* Archivo Redo Logs

## Tipos de uso

* Modo Target (Contolfile)
* Modo Catalogo

## Configurar el directorio donde nuestros respaldos se van a almacenar
````SQL
ALTER SYSTEM SET DB_RECOVERY_FILE_DEST_SIZE = 10G;
ALTER SYSTEM SET DB_RECOVERY_FILE_DEST 'RUTA_DE_DESTINO'
````
## Backups Incrementales

* Backup incremental o/completo (TODO)
* Backup diferencial
* Backup acumulativo (Contiente todos los diferenciales)
