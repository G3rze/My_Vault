---
date: 2024-10-16
tags: #web-programming #pw202024 #mondongo #JavaScript
  -
hubs: "[[PW022024|PW022024]]"
urls:
  -
---

# JavaScript-as-a-Language


## ¿Qué es JavaScript?

* Es un lenguaje multiplataforma
* Orientado a Objetos
* Es para scripting
* Agrega interaciónes en páginas web
* Server-side/Client-side

## Client-Side JavaScript:

* Manipula elementos del navegador como objetos (DOM)
* Añade dinamismo e interactividad a la web
    * Manipulación de elementos HTML
    * Manejo de eventos de usuari

## Server-Side JavaScript

* Se maneja por medio de Frameworks como Node.Js
* Se enfoca en funcionabilidades web
    * Colaboración a tiempo real entre varias computadoras
    * Maneja operaciones de servidores (Comunicaciónes de bases de datos, manipulación de archivos, etc.)

## Caracteristicas Clave

* Librerias de objetos estandar (Array, Math, etc)
* Mantiene el estandar de lenguajes modernos (Operadores, If, Swiths, While,etc.)
* Puede ampliarse con nuevos objetos
* En el cliente Js trabaja con el DOM de manera dinamica
* En el servidor maneja peticiones personalizadas entre el servidor y el clientte (Node.js)

![[Pasted image 20241016182342.png]]

## Estandarizaciones de JavaScript

### ECMAScript

* ECMA-262 or ISO-16262 (Nombre Js estandarizado)
* Detalla como se tiene que implementar Js como motor de navegadores
* Es especifico para los que trabajan con motores de Js (No scripts/No DOM)

### JavaScript Documentation

* Destinado al programador web común

* No son numerables* Usos practicos y estandarizados
* Si incluye el uso del DOM y otras APIs web

## Manejo de Errores y Execpciones
* Throw Statement  (Lanza la exception)
* Try...Catch (Si no sabes que es cambiate de carrera)
### Tipos de Excepciones
* ECMAScript exceptions
* DOMException

## Expresiones regulares (REGEX)

* Simbolos usados para busqueda, validaciones o reemplazar texto

## ¿Quién putas es JSON?

* JavaScript Object Notation
* Formato de intercambio de datos ligero
* Es legible por humanos
* Es independiente del lenguaje, cada lenguaje tiene sus librerias para traducirlo
* Usan el formato clave valor

## Symbols (Simbolos)

* Cuando se declaran no pueden cambiarse
* No se pueden haber dos simbolos con el mismo valor
* Hay simbolos pre-hechos en Js (Well-Known symbols)
* No son numerables

```Js
const sym1 = Symbol("value")
```
