# Simulador Cuántico

Este repositorio contiene una implementación en Python de un simulador cuántico capaz de realizar diversas operaciones como:

- Representación y normalización de un estado cuántico.
- Cálculo de la **probabilidad de encontrar una partícula** en una posición específica.
- Cálculo de la **probabilidad de transición** entre estados cuánticos.
- Verificación de la **hermiticidad** de una matriz.
- Cálculo de la **media y varianza** de un observable.
- Obtención de **valores propios** y probabilidad de transición a estados propios.
- Simulación de la **evolución temporal** de un estado cuántico bajo operadores unitarios.

## Instalación de dependencias

Este proyecto utiliza la librería `numpy` y `matplotlib` para realizar cálculos matriciales. Si no la tienes instalada, puedes hacerlo con:

```sh
pip install numpy
```

```sh
pip install matplotlib
```

## Contenido del repositorio

El código está organizado en los siguientes notebooks de Jupyter:

### 1. **Simulador Cuántico (Simulador.ipynb)**
Este notebook implementa la clase principal para la simulación de sistemas cuánticos discretos. Incluye:
- Estado cuántico y normalización.
- Medición y cálculo de probabilidades.
- Probabilidad de transición entre estados.
- **Ejemplo 1**: Cálculo de la probabilidad en cada posición.
- **Ejemplo 2**: Probabilidad de transición entre dos estados.

### 2. **Discusión de Ejercicios (Discusion_ejercicios.ipynb)**
Contiene una explicación detallada de problemas fundamentales en mecánica cuántica y su resolución.

### 3. **Problemas Modelados (problemas_modelados.ipynb)**
Incluye problemas resueltos utilizando el simulador y su aplicación en situaciones físicas concretas.

### 4. **Retos de Programación (Retos Programacion.ipynb)**
Desafíos adicionales para profundizar en la implementación de algoritmos cuánticos.

## Uso del Simulador

Para utilizar el simulador, simplemente importa la clase correspondiente y define un estado cuántico inicial. Por ejemplo:

    import numpy as np
    from simulador import SistemaCuantico

    estado_inicial = np.array([[1], [0]])
    sistema = SistemaCuantico(estado_inicial)

Puedes ejecutar los notebooks en Jupyter Notebook con los distintos ejemplos y problemas planteados.


