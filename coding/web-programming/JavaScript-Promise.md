---
date: 2024-10-16
tags: #web-programming #JavaScript #pw022024 #mondongo
    -
hubs:
     "[[PW022024]]"
urls:
    -
---

# JavaScript-Promise

## Modelos de Programación

### Secuencial

* Una tarea después de otra
* Cada tarea tiene que completarse para empezar la otra
* Simple pero ineficiente para multiples operaciones

### Concurrente

* Varias tareas avanzan en un mismo espacio de tiempo
* Tienen un control de rendimiento

### Paralelo

* Multiples tareas se ejecutan en el mismo tiempo (en distintos hilos de procesamiento)
* A diferencia del concurrente este es verdaderamente simultaneo

## Comparación final

* Sequencial (Lineal/Una tarea a la vez)
* Concurrente (Muchas tareas se ejecutan en un bloque de tiempo)
* Pararelo (Muchas tareas se ejecutan en el mismo tiempo, pero en distintos procesos)

## Promesas en JavaScript

* Un objeto que representa la eventual ejecución de una operación asincrona
* Tiene 3 estados
    * Pending (Estado inicial)
    * Fulfilled (Se logró)
    * Rejected (No se logró)
* Metodos
    * then() => En caso de que haya logrado
    * catch() => Si no se logró
    * finally() => En cualquiera de ambos casos

## Async/Await

* Simplifican trabajar con tareas asincronas
* Se introdujo con ECMAScript 2017
* Async hace que una función devuelva una promesa y permite el uso del await
* Await pausa la ejecución de la función hasta que la promesa se resuelva
* No pausa el hilo principal de trabajo
* Se usa try-catch para la exepciones de estas funciones
* Se pueden utilizar varios await para paralelizar las ejecuciones de promesas
* Promise.all() afecta a todas las promesas de la función

## Conclusión

* Async/Await simplifica trabajar con codifo asincrono
* Async/Await se utiliza por encima de las promesas para mejorar su control
* Si se necesita paralelismo Promise.all() afecta a todas las promesas


