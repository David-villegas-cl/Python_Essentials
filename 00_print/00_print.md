# Función print()

![FUNCIÓN_PRINT](../00_media/PY_PRINT.webp)

La función `print()` en Python en una herramienta fundamental para mostrar información en la consola o un archivo de salida. Se utiliza para imprimir texto, variables, valores y resultados de cálculos. Es uan de las funciones más básicas y utilizadas en Python.

1. **Imprimir un mensaje simple en consola**.

    ```python
    print("Hola, mundo!")
    ```
2. **Imprimir el valor de una variable**.

    ```python
    numero = 10
    print(numero)
    ```
3. **Imprimir varios elementos con separadores**.

    ```python
    nombre = "Juan"
    apellido = "Pérez"
    edad = 34

    print(nombre, apellido, edad)
    ````

## Funciones de impresión formateadas

Python ofrece funcionalidades para formatear la salida de la función `print()`. Se puede utilizar cadenas formateadas con el símbolo `f` o el método `format()`.

1. **Cadenas formateadas**.

    ```python
    nombre = "Maria"
    edad = 25

    print(f"El nombre es {nombre} y la edad es {edad}")
    ```

2. **Método `format()`**.

    ```python
    nombre = "Pedro"
    ciudad = "Santiago"

    mensaje = "Hola, {} de {}.format(nombre, ciudad)"
    print(mensaje)
    ```

## [HAZ CLICK AQUÍ PARA IR A LOS EJERCICIOS](00_print.py)