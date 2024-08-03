# Tipos de datos en Python

![TIPOS_DE_DATOS](../00_media/PY_DATOS.webp)

En Python, los tipos de datos son elementos básicos que se utilizan para almacenar y manipular información. Cada tipo de dato tiene sus propias características y propiedades, y se utilizan para representar diferentes tipos de información, como números, texto, listas, etc.

## Tipos de datos básicos

### Numéricos

- Enteros `int`: números enteros positivos o negativos sin decimales.

    ```python
    edad = 30
    numero_negativo = -10
    ```

- Decimales `float`: Números con decimales.

    ```python
    pi = 3.14159
    altura = 1.75
    ```

- Complejos `complex`: Números complejos que representan la suma de una parte real y una parte imaginaria.

    ```python
    z = 3+2j
    ```

### Cadenas de texto

- Cadenas de texto `str`: secuencia de caracteres encerrados entre comillas simples o dobles.

    ```python
    nombre = "Juan"
    mensaje = "Hola, mundo!"
    ```

### Booleanos

- Booleanos `bool`: Representan valores lógicos de verdad o falsedad, y se utilizan para indicar si una condición es verdadera o falsa. Los valores posibles son `True` o `False`.

    ```python
    es_mayor_de_edad = True
    esta_lloviendo = False
    ```

## Tipos de datos compuestos

- Listas `list`: Colecciones ordenadas de elementos de cualquier tipo, encerrados entre corchetes `[]`. Se pueden modificar (agregar, eliminar o modificar elementos).

    ```python
    frutas = ["Manzana", "Plátano", "Pera"]
    numeros = [1, 2, 3, 4, 5]
    ```

- Tuplas `tuple`: Colecciones ordenadas e inmutables (no se pueden modificar) de elementos de cualquier tipo, encerrados entre paréntesis `()`.

    ```python
    coordenadas = (3, 5)
    dias_semana = ("Lunes", "Martes", "Miércoles", "Jueves", "Viernes")
    ```

- Diccionarios `dict`: Colecciones no ordenadas de pares clave-valor, encerrados entre llaves `{}`. Cada elemento del diccionario tiene una clave única y un valor asociado.

    ```python
    persona = {"nombre": "Juan", "edad": 30, "altura": 1.75}
    ```

- Colecciones `set`: Colecciones no ordenadas de elementos únicos, encerrados entre llaves `{}`. Se utilizan para almacenar elementos sin duplicados.

    ```python
    vocales = {"a", "e", "i", "o", "u"}
    ```

### Objetos

Los objetos son instancias de clases definidas por el usuario. Representan entidades abstractas con sus propios atributos y métodos. Se utilizan para encapsular datos y comportamientos relacionados.

### Conclusión

Los tipos de datos en Python son esenciales para comprender y trabajar con información en programas. Cada tipo de dato tiene sus propias características y usos específicos. Saber elegir el tipo de dato adecuado para cada caso fundamental para escribir programas eficientes y fáciles de mantener.

## [CLICK AQUÍ PARA IR A LOS EJERCICIOS](02_tipos_datos.py)