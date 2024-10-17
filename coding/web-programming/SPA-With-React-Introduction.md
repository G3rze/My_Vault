---
date: 2024-10-16
tags: #web-programming #pw022024 #ReactJs #JavaScript #Mondongo #SPA
    -
hubs:
     "[[PW022024]]"
urls:
    -
---

# SPA-With-React-Introduction


## Introducción a React

* Libreria de JavaScript para UIs
* Principalmente para SPAs
* Open Source desde 2013
* Se enfoca solo en la UI (no es tan completo como otros frameworks)
* Se basa en un estructura de componentes
* Virtual DOM (DOM en caché)

## Conceptos clave de React
* Componentes (Los bloques que contruyen la aplicación)
* State (Como se manejan los datos de los componentes)
* Props (Propiedades que se pasan entre componentes mayormente datos)

## Components en React

* Son bloques de codigo reutilizables
* Cada componente es una parte de la UI

### Tipos de componentes
* Functional Components (Componentes simples que se definen como funciones)
* Class Components (Componentes complejos que tienen metodos de ciclos de vida)

## Functional Components
```Js
// Example of a functional component
function Greeting() {
  return <h1>Hello, World!</h1>;
}

export default Greeting;

```
* No tienen estado de default
* Pueden manejar estados y ciclos de vida con el uso de Hooks

## Class Components

```Js
// Example of a class component
import React, { Component } from 'react';

class Greeting extends Component {
  render() {
    return <h1>Hello, {this.props.name}!</h1>;
  }
}

export default Greeting;

```

* Permiten el uso de estados y de metodos del ciclo de vida directamente
* Con el uso de React Hooks el uso de estas es menos común

## State in React

* Los estados son usados para cambiar los datos internos de un componente

## Props in React

* Son usados para pasar datos del componente padre al hijo
* Los props son read-only, el hijo no los puede modificar

## ¿Qué es Vite?

* Optimiza frameworks de frontend
* Utiliza ES Modules nativos del navegador (no corren en el server)
* Solo se compila el codigo que se esta usando
* Reemplazo de modulos en caliente cuando ya no se usan (HMR)
* Sistema de plugins de la comunidad

## Setting Up React with Vite

![[Pasted image 20241016203717.png]]
![[Pasted image 20241016203740.png]]

## Ventajas de React

* Arquitectura basada en Componentes
* Virutal DOM
* Desarrollo rápido
* Ecosistema fuerte

## Desventajas de React

* Curva de aprendizaje
* Complejidad en aplicaciones grandes
* SEO (Favorece a las Server-Side Rendering SSR)

## Introducción a npm

* Node Package Manager npm
* Es el administrador de paquetes por defecto de Node.js
* Permite instalar, manejar y compartir paquetes
* Tiene un registro masivo de paquetes
* Utiliza un package.json para definir todos los paquetes del proyecto
* Permite automatizar tareas como los tests

## Introducción a Yarn

* Otro administrador de paquetes creado por Meta
* Rapido y más facil de usar
* Tiene todo lo de npm y más
* Permite instalaciones en paralelo
* Usa un arbol de dependencias
* Previene errores de versiones asegurando que la misma versión sea descargada cuando se requiera

## Introducción a React Hooks

* Permite que los functional components puedan usar estados y otras caracteristicas de React
* Hooks Comunes
    * useState
    * useEffect
    * useMemo
    * useContext

## useState Hook

* Se usa para declarar estados en **functional components**
* Los efectos secundarios incluyen:
    * Busqueda de datos de una API
    * Subscripciones
    * Manipular el DOM

## useMemo Hook

* Memoriza calculos costosos
* Retorna datos memorizados (Solo lo recalcula si las dependencias cambian)

## useContext Hook

* Permite enviar estados entre componentes sin usar props
* Da acceso al contexto más cercano

## Creación de Hooks Personalizados

* Permiten extraer y reusar la logica de los componentes
* Son funciones de Js que usan React Hooks
* Por convensión su nombre empieza con use

## ¿Qué es useReducer?
* Alternativa a useState para manejar una logica de estados multiples


