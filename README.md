# Teoría cuántica básica Observables y Medidas

## Descripción

Este proyecto implementa simulaciones de sistemas cuánticos discretos, enfocándose en la representación de estados, el cálculo de probabilidades de transición y la evolución dinámica bajo operadores cuánticos.

Se desarrollaron algoritmos en Python para:

- Calcular la probabilidad de encontrar una partícula en una posición determinada.

- Determinar la probabilidad de transición entre dos estados cuánticos.

- Verificar si un operador es hermitiano y calcular su valor esperado y varianza.

- Calcular los autovalores y la distribución de probabilidades sobre los autovectores del operador.

- Aplicar la evolución temporal de un sistema mediante matrices unitarias.

## Simulaciones Implementadas

**Representación del Estado Cuántico**

- Se modela un sistema con un conjunto discreto de posiciones en una línea.

- Se define un vector ket inicial con amplitudes de probabilidad.

**Probabilidad de Posición**

- Se calcula la probabilidad de encontrar la partícula en una posición determinada usando el cuadrado del módulo de las amplitudes del ket.

**Probabilidad de Transición**

- Se permite ingresar dos estados cuánticos y calcular la probabilidad de transitar del primero al segundo.

**Operadores Hermitianos y Observables**

- Se implementa la verificación de que un operador es hermitiano.

- Se calcula el valor esperado y la varianza de un observable en un estado dado.

**Autovalores y Probabilidades de Medición**

- Se obtienen los valores propios de un operador y se calcula la probabilidad de que el sistema colapse en cada uno de sus autovectores tras una medición.

## Evolución Temporal del Sistema

- Se permite aplicar una serie de matrices unitarias al estado inicial y calcular el estado final del sistema.

## Requisitos

- Software Python 3.8 o superior

## Librerías utilizadas

- NumPy → Para operaciones con vectores y matrices.

- SciPy → Para funciones matemáticas avanzadas.

## Equipo Utilizado

Computador Dell, i7 11th Gen, 24 GB RAM, pantalla 15.6''

## Aclaración

Este proyecto está diseñado para fines educativos y de desarrollo local.

## Autor

Juan Sebastián Fajardo Acevedo: Trabajo inicial y mantenimiento del proyecto.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT. Para más detalles, consultar el archivo LICENSE.md.

## gradecimientos

Este proyecto fue inspirado por cursos de mecánica cuántica, álgebra lineal y teoría de operadores.

Agradecimientos especiales a la comunidad de Python por sus excelentes bibliotecas.

## Referencias

- Notas del curso de Computación Cuántica y Teoría de cuántica básica Observables y Medidas.

- Feynman Lectures on Physics: http://www.feynmanlectures.caltech.edu/

- NumPy: https://numpy.org/

- SciPy: https://scipy.org/

- Qiskit: https://qiskit.org/
