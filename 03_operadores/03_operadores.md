# Operadores en Python

![OPERADORES](../00_media/PY_OPERADORES.webp)

En Python los operadores son símbolos que se utilizan para realizar operaciones con valores o variables. Se pueden clasificar en diferentes categorías según el tipo de operación que realizan. Los operadores más comunes en Python son los aritméticos, de comparación, lógicos y de asignación.

## Operadores aritméticos

Los operadores aritméticos se utilizan para realizar operaciones matemáticas con valores numéricos. Los operadores aritméticos más comunes en Python son:

- Suma `+`: Suma de valores.
- Resta `-`: Resta de valores.
- Multiplicación `*`: Multiplicación de valores.
- División `/`: División de valores.
- División entera `//`: División entera de valores.
- Residuo `%`: Residuo de la división.
- Potencia `**`: Potencia de un número.

**Ejemplo de operadores aritméticos**:

```python
resultado = 10 + 5
resta = 15 - 4
multiplicacion = 3 * 5
division = 16 / 4
residuo = 10 % 3
```

## Operadores de comparación

- Igualdad `==`: Compara si dos valores son iguales.
- Diferente `!=`: Compara si dos valores son diferentes.
- Mayor que `>`: Compara si un valor es mayor que otro.
- Menor que `<`: Compara si un valor es menor que otro.
- Mayor o igual que `>=`: Compara si un valor es mayor o igual que otro.
- Menor o igual que `<=`: Compara si un valor es menor o igual que otro.

**Ejemplo de operadores de comparación**:

```python
es_igual = 10 == 10
es_diferente = 5 != 3
es_mayor = 15 > 10
es_menor = 5 < 10
```

## Operadores lógicos

- AND `and`: Devuelve `True` si ambas condiciones son verdaderas.
- OR `or`: Devuelve `True` si al menos una condición es verdadera.
- NOT `not`: Devuelve `True` si la condición es falsa.

**Ejemplo de operadores lógicos**:

```python
esta_lloviendo = True
tiene_hambre = False

si_esta_lloviendo_y_tiene_hambre = esta_lloviendo and tiene_hambre
si_esta_lloviendo_o_tiene_hambre = esta_lloviendo or tiene_hambre
si_no_tiene_hambre = not tiene_hambre
```

## Operadores de pertenencia

- `in`: Devuelve `True` si un valor se encuentra en una secuencia.
- `not in`: Devuelve `True` si un valor no se encuentra en una secuencia.

**Ejemplo de operadores de pertenencia**:

```python
frutas = ['manzana', 'pera', 'uva']
esta_en_la_lista = 'manzana' in frutas
no_esta_en_la_lista = 'sandia' not in frutas
```

## Operadores de asignación

- Asignación simple: `=`
- Asignación aditiva: `+=`
- Asignación sustractiva: `-=`
- Asignación multiplicativa: `*=`
- Asignación divisiva: `/=`
- Asignación de división entera: `//=`
- Asignación de residuo: `%=`
- Asignación de potencia: `**=`

**Ejemplo de operadores de asignación**:

```python
numero = 10
numero += 5
numero -= 3
numero *= 2
numero /= 4
```

## Operadores especiales

- Paréntesis para agrupar operaciones: `()`
- Corchetes para acceder a elementos de una lista: `[]`
- Llaves para acceder a elementos de un diccionario: `{}`
- Decorador para funciones: `@`
- Inicio de comentario de una línea: `#`

## [CLICK AQUÍ PARA IR A LOS EJERCICIOS](03_operadores.py)