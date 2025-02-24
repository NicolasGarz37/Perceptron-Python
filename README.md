# Perceptrón para compuertas AND y OR en pyhton
Implementación de perceptrón para crear un modelo que resuelva la compuerta AND y OR.
- Compuertas AND y OR
  
  Son operaciones lógicas que utilizamos en la programción y en el diseño de circuitos.
  
  - AND: En ésta compuerta la salida solo es 1 cuando ambas entradas son 1, de lo contrario la salida es 0.

  - OR: En ésta compuerta la salida es 1 cuando al menos una entrada es 1, cuando las dos entradas son 0 la salida es 0.

## Requisitos
- Google colab
- Cualquier entorno en el que se pueda desarrollar el lenguaje de python.

## Descripción
El perceptrón es un modelo de red neuronal artificial(RNA) capaz de aprender funciones linealmente separables. En este caso, se entrena para aprender el comportamiento de las compuertas lógicas AND y OR.

## Implementación
El código implementa:
- Un perceptrón de una sola neurona
- Entrenamiento con el algoritmo de aprendizaje de perceptrón
- Predicción de salida para entradas dadas
- Aplicación en compuertas AND y OR

## Uso
1. Clone el .ipynb del repositorio (Perceptron.ipynb).
2. Ejecuta el script en pyhton.
3. Observe los resultados.

## Ejemplo de salida esperada
![image](https://github.com/user-attachments/assets/97b4ccdd-b5eb-4859-8726-ae3a53b9ba5e)

Compuerta AND:
Entrada: [0, 0], Salida: 0
Entrada: [0, 1], Salida: 0
Entrada: [1, 0], Salida: 0
Entrada: [1, 1], Salida: 1

Compuerta OR:
Entrada: [0, 0], Salida: 0
Entrada: [0, 1], Salida: 1
Entrada: [1, 0], Salida: 1
Entrada: [1, 1], Salida: 1

## Archivos disponibles
Perceptrón.ipynb el script crear un modelo que resuelva la compuerta AND y OR.
