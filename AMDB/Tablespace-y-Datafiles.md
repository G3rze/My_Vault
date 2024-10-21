---
date: 2024-10-21
tags: #AMDB #Oracle #Tablespaces #Datafiles #DB #SQLDB
    -
hubs:
     "[[AMDB_HUB]]"
urls:
    -
---

# Tables-y-Datafiles

## Objetivos

* Administrar tablespaces
* Entender la estructura de un datafile
* Relacionar los tablespaces con lo datafiles
* Conocer las diferentes posibilidades para gestionar los tablespaces

## Graficos

### Simplificado

![[Pasted image 20241021093427.png]]

### Expandido

![[Pasted image 20241021093506.png]]

## Tablespace

* Es una unidad lógica de almacenamiento de Oracle
* Almacena uno o más **datafiles**
* Organiza y gestiona la DB
* Las tablas e índices se almacenan en un tablespace
* Se puede ajustar su tamaño
* Los objetos se pueden mover entre tablespaces

## Datafie

* Archivo fisico en el SO
* Almacena datos reales de la DB
* Puede estar asociado con un o más datafiles


* Organiza y gestiona la DB
* Las tablas e índices se almacenan en un tablespace
* Se puede ajustar su tamaño
* Los objetos se pueden mover entre tablespaces

## Datafie

* Archivo fisico en el SO
* Almacena datos reales de la DB
* Puede estar asociado con un o más datafiles

![[Pasted image 20241021094432.png]]

## Tipos de Tablespaces

* **SYSTEM y SYSAUX** => Contienen los objetos necesarios para la operación de la DB

* **Tablespaces de Usuario** => Almacenan los datos de los usuarios

* **TEMP** => Almacenan datos temporales generados por operaciones en la DB

* **UNDO** Continen información necesaria para deshacer transacciones


