---
date: 2024-10-21
tags: #AMDB #Oracle #Tablespace #Controlfiles #DB #SQLDB #Storage
    -
hubs:
     "[[AMDB_HUB]]"
urls:
    -
---

# Controlfiles

## Definición

* Son archivos binarios críticos que almacenan información sobre la estructura física de la DB
* Contienen metadatos que permiten la gestión y recuperación de la DB en caso de fallos
* Se recomienda tener multiples copias en diferentes discos

## ¿Qué almacenan?

* Nombre de la DB
* Nombre y ubicación de los Datafiles y los RedoLog
* Fecha de creación de la DB
* RedoLogs disponibles
* Información de Checkpoints
* Otras cosas importantes

![[Pasted image 20241021103635.png]]

![[Pasted image 20241021104947.png]]

## Etapas de inicialización de instancia de Oracle

* **SHUTDOWN** => Apaga una instancia de base de datos
* **STARTUP NOMOUNT** => Crear una nueva base de datos o ejecutar procedimientos
* **STARTUP MOUNT** => Operaciones de mantenimiento de la DB
* **STARTUP OPEN** => Modo estándar en el que se inicia la base de datos

![[Pasted image 20241021105024.png]]

## Modos de apagado de la instancia de Oracle

![[Pasted image 20241021105604.png]]