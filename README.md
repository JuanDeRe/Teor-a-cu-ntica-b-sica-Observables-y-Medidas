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

Este proyecto utiliza la librería `numpy` para realizar cálculos matriciales. Si no la tienes instalada, puedes hacerlo con:

```sh
pip install numpy
```

## Contenido del repositorio

El código está organizado en los siguientes notebooks de Jupyter:

### **1. Simulador Cuántico (`Simulador.ipynb`)**
Este notebook implementa la clase principal para la simulación de sistemas cuánticos discretos. Incluye:
- Estado cuántico y normalización.
- Medición y cálculo de probabilidades.
- Probabilidad de transición entre estados.
- **Ejemplo 1**: Cálculo de la probabilidad en cada posición.
- **Ejemplo 2**: Probabilidad de transición entre dos estados.

### **2. Retos de Programación (`Retos Programacion.ipynb`)**
Contiene la resolución de los siguientes retos de programación:
1. **Probabilidad de Transición** entre dos estados cuánticos.
2. **Media y Varianza de un Observable** aplicando operadores hermitianos.
3. **Valores Propios y Probabilidad de Colapsar** en los estados propios de un operador.
4. **Evolución del Estado Cuántico** con una serie de operadores unitarios.

## Cómo ejecutar los notebooks

Para ejecutar los notebooks, simplemente abre los archivos Simulador.ipynb o Retos Programacion.ipynb en Jupyter Notebook y corre cada bloque de código por separado.

## Notas

- Todos los cálculos se realizan en el espacio de números complejos.
- Se asume que los operadores de evolución son matrices unitarias de tamaño compatible con el estado cuántico.

