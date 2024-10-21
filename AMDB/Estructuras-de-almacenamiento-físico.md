---
date: 2024-10-21
tags: #ORACLE #AMDB #Creatina #DB #SQLDB
    -
hubs:
     "[[AMDB_HUB]]"
urls:
    -
---

# Estructuras-de-almacenamiento-físico

## Diagramas

![[Pasted image 20241021095648.png]]

![[Pasted image 20241021095717.png]]

## Bloques

* Unidad mínima de almacenamiento en Oracle
* Cada dato que se almacena lo hace en forma de bloque
* Contiene filas de una tabla o indices
* Pueden almacenar una o más filas (dependiendo del tamaño)
* Su tamaño es configurables (*Normalmente son de 2KB, 4KB, 8KB, 16KB o 32KB*)

## Extensiones

* Son un conjunto contiguo de bloques
* Permiten que un objeto crezca de manera controlada
* Se gestionan automaticamente por oracle
* Su tamaño puede ser uniforme o variable respecto a otras extensiones

## Segmentos

* Son un cojunto de extensiones que se asignan a una estructura lógica (tabla, indice, tabla temporal, etc)
* Cada objeto que almacena datos esta asociado a uno o más segmentos

![[Pasted image 20241021101259.png]]


![[Pasted image 20241021101612.png]]

## Conclusión

Entender la distribución de los datos y el almacenamiento es importante para poder administrar mejor el espació, realizar tareas de recuperación, etc.