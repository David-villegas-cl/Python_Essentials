# Tuplas

Las tuplas en Python son un tipo de dato **inmutable** que se utilizan para almacenar colecciones ordenadas de elementos. A diferencia de las listas, las tuplas no se pueden modificar una vez creadas. Son útiles para representar datos que no cambian con el tiempo, como coordenadas, direcciones o información de configuración.

## ¿Cómo se crean las tuplas?

Las tuplas se crean utilizando paréntesis `()` y separando los elementos por comas `,`, no es necesario especificar el tipo de datos de los elementos, ya que Python los infiere automáticamente a partir de los valores proporcionados.

**Ejemplo de creación de tuplas:**

```python
frutas = ("manzana", "pera", "naranja")
numeros = (1, 2, 3, 4, 5)
mezcla = ("hola", 3, True, 2.5)
```

## ¿Cómo acceder a los elementos de una tupla?

Se puede acceder a los elementos de una tupla utilizando su índice. El índice comienza en `0` y se puede acceder al último utilizando la longitud de la tupla menos uno.

**Ejemplo de acceso a elementos de una tupla:**

```python
# Acceso a elementos individuales por su índice
primera_fruta = frutas[0]
segundo_numero = numeros[1]
ultimo_elemento = mezcla[-1]

# Acceso a un rango de elementos
subtupla = frutas[1:3]
```

## ¿Cuales son las operaciones que se pueden realizar con tuplas?

Las tuplas en Python soportan operaciones básicas, como:

```python
frutas = ("manzana", "pera", "naranja")
frutas1, frutas2, frutas3 = frutas
print(f"Fruta 1: {frutas1}")
print(f"Fruta 2: {frutas2}")
print(f"Fruta 3: {frutas3}")
```

