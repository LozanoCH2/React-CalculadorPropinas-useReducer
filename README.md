# Calculadora de Propinas - Migración a useReducer

Este proyecto consiste en la migración de una calculadora de propinas, originalmente construida con un hook personalizado, a utilizar el hook `useReducer` de React. Esta migración se realizó para mejorar la eficiencia y optimizar el rendimiento de la aplicación. El uso de `useReducer` permite una mejor gestión del estado y simplifica el manejo de acciones complejas en la aplicación.

Puedes ver la aplicación en acción [aquí](https://react-calculadora-propinas.netlify.app).

## Tabla de Contenidos

- [Descripción del Proyecto](#descripción-del-proyecto)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Instalación](#instalación)
- [Funcionalidades](#funcionalidades)
- [Ventajas de useReducer](#ventajas-de-usereducer)
- [Créditos](#créditos)
- [Conclusión](#conclusión)

## Descripción del Proyecto

La Calculadora de Propinas es una aplicación web que permite a los usuarios seleccionar alimentos para añadir a una orden de consumo. A medida que se agregan alimentos, la aplicación calcula el total a pagar basado en la cantidad y el precio de cada alimento. Además, los usuarios pueden:

- **Eliminar Alimentos**: Quitar un alimento específico de la orden.
- **Seleccionar un Porcentaje de Propina**: Elegir el porcentaje de propina que desean dejar.
- **Calcular el Total a Pagar**: La aplicación calcula automáticamente el subtotal, la propina y el total a pagar, facilitando así el manejo de las cuentas.

## Tecnologías Utilizadas

- **React**: Biblioteca de JavaScript para construir interfaces de usuario.
- **useReducer**: Hook de React utilizado para gestionar el estado de la aplicación de manera eficiente.
- **Tailwind CSS**: Framework de CSS para estilizar la interfaz de manera rápida y responsiva.

## Instalación

Para ejecutar este proyecto localmente, sigue estos pasos:

1. Clona el repositorio:
    ```bash
    git clone https://github.com/tuusuario/calculadora-propinas-migracion-usereducer.git
    ```
2. Navega al directorio del proyecto:
    ```bash
    cd calculadora-propinas-migracion-usereducer
    ```
3. Instala las dependencias:
    ```bash
    npm install
    ```
4. Inicia el servidor de desarrollo:
    ```bash
    npm run dev
    ```

## Funcionalidades

- **Agregar Alimentos a la Orden**: Los usuarios pueden seleccionar alimentos para añadirlos a la orden de consumo.
- **Eliminar Alimentos**: Permite quitar un alimento específico de la orden.
- **Seleccionar Porcentaje de Propina**: Los usuarios pueden elegir el porcentaje de propina que desean dejar.
- **Cálculo Automático**: Calcula automáticamente el subtotal, la propina y el total a pagar.

## Ventajas de useReducer

Migrar la aplicación a `useReducer` trajo varias ventajas significativas:

- **Gestión Centralizada del Estado**: `useReducer` centraliza la lógica del estado, facilitando la gestión y la consistencia en la aplicación.
- **Uso de Acciones Claras**: La utilización de acciones (`add`, `remove`, `updateTip`, `calculateTotal`) permite un manejo más estructurado y predecible del estado.
- **Optimización del Código**: `useReducer` simplifica el código, especialmente en aplicaciones con lógica compleja, mejorando la legibilidad y el mantenimiento.

## Créditos

Este proyecto fue desarrollado como parte del curso de React y TypeScript de [codigoconjuan](https://codigoconjuan.com). Agradezco el conocimiento y los recursos proporcionados durante el curso, que me permitieron mejorar mis habilidades y optimizar esta aplicación.

## Conclusión

La migración de la Calculadora de Propinas a `useReducer` fue una experiencia enriquecedora que me permitió aprender y aplicar las ventajas de este hook en la optimización de aplicaciones React. Este enfoque no solo mejoró el rendimiento, sino que también simplificó la lógica del estado, haciéndola más escalable y mantenible para proyectos futuros.
