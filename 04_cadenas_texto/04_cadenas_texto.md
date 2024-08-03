# Cadenas de texto

![CADENAS_DE_TEXTO](../00_media/PY_CADENAS.webp)

Las cadenas de texto (strings en inglés) son un tipo de dato básico en Python. Se utilizan para representar secuencias de caracteres, como palabras, frases, párrafos, entre otros. En Python, las cadenas de texto se pueden definir utilizando comillas simples (`'`) o dobles (`"`).

**Ejemplo de cadenas de textos simples**.

```python
cadena1 = 'Hola, mundo!'
cadena2 = "¡Hola, Python!"
cadena3 = 'Este es un texto con "comillas" dentro.'
```

## Acceso a caracteres

Se puede acceder a caracteres individuales de una cadena de texto utilizando el operador de índice `[]`. El índice comienza en `0`, y se puede acceder al último carácter usando la longitud de la cadena menos uno.

**Ejemplo de acceso a caracteres**.

```python
cadena = 'Hola, mundo!'

# Accediendo al primer carácter
primer_caracter = cadena[0]

# Accediendo al último carácter
ultimo_caracter = cadena[-1]

# Accediendo a un rango de caracteres
subcadena = cadena[3:6]
```

## Operaciones de cadenas de texto

Python ofrece una amplia gama de operaciones que se pueden realizar con cadenas de texto, incluyendo:

- Concatenación: Unir dos o más cadenas de texto.
- Repetición: Repetir una cadena de texto un número especifico de veces.
- Interpolación: Insertar variables o expresiones dentro de una cadena de texto.
- Reemplazo: Reemplaza un patrón o subcadena dentro de una cadena de texto.
- Mayúsculas y minúsculas: convertir una cadena de texto a mayúsculas o minúsculas.
- Eliminación de espacios: Eliminar espacios en blanco al inicio y final de una cadena de texto.
- División: Dividir uan cadena de texto en una lista de subcadena según un delimitador.

## Funciones de cadenas de texto

Python proporciona una biblioteca de funciones integradas para trabajar con cadenas de texto. Algunas de las funciones más comunes son:

- `len(cadena)`: Devuelve la longitud de la cadena de texto.

    ```python
    cadena = 'Hola, mundo!'
    # Calcular la longitud de la cadena
    longitud = len(cadena)
    # Imprimir la longitud de la cadena
    print(longitud)
    ```

- `upper(cadena)`: Convierte la cadena de texto a mayúsculas.

    ```python
    cadena = 'Hola, mundo!'
    cadena_mayusculas = cadena.upper()
    print(cadena_mayusculas)
    ```

- `lower(cadena)`: Convierte la cadena de texto a minúsculas.

    ```python
    texto = "Hola, Mundo! ¿Cómo estás?"
    # Convertir el texto a minúsculas
    texto_minusculas = texto.lower()
    # Imprimir el resultado
    print(texto_minusculas)
    ```

- `strip(cadena)`: Elimina los espacios en blanco al inicio y final de la cadena de texto.

    ```python
    cadena_con_espacios = "  Hola, mundo!   "
    # Eliminar los espacios en blanco
    cadena_sin_espacios = cadena_con_espacios.strip()
    # Imprimir el resultado
    print(cadena_sin_espacios)
    ```

- `find(cadena1, cadena2)`: Busca la subcadena `cadena2` dentro de `cadena1`.

    ```python
    texto = "El rápido zorro marrón salta sobre el perro perezoso."
    subcadena = "zorro"
    # Buscar la subcadena en el texto
    indice = texto.find(subcadena)

    if indice != -1:
        print("la subcadena '{}' se encontró en el índice {}".format(subcadena, indice))
    else:
        print("la subcadena '{}' no se encontró".format(subcadena))
    ```


- `replace(cadena1, cadena2, cadena3)`: Reemplaza todas las ocurrencias de `cadena2` por `cadena3` en `cadena1`.

    ```python
    cadena_original = "Hola, mundo cruel!"
    cadena_nueva = cadena_original.replace("mundo", "Python")

    print("Cadena original:", cadena_original)
    print("cadena reemplazada:", cadena_nueva)
    ```

- `split(cadena, delimitador)`: Divide la cadena de texto en una lista de subcadenas según el delimitador.

    ```python
    texto = "Python, Java, Javascript"
    # Divide la cadena en una lista, usando la coma (,) como separador
    lenguajes = texto.split(",")
    # Imprimir la lista de lenguajes
    print(lenguajes)
    ```

- `capitalize(cadena)`: Convierte la primera letra de la cadena de texto a mayúsculas.

    ```python
    texto = "hOla, mUnDo!"
    texto_capitalizado = texto.capitalize()
    print(texto_capitalizado)
    ```

- `title(cadena)`: Convierte la primera letra de cada palabra de la cadena de texto a mayúsculas.

    ```python
    texto = "este es un título"
    print(texto.title())
    ```

- `count(cadena1, cadena2)`: Cuenta el número de ocurrencias de `cadena2` en `cadena1`.

    ```python
    texto = "Hola, mundo! Cómo estás hoy?"
    #Contamos el número de ocurrencias de la letra 'o'
    cantidad_o = texto.count('o')
    print("Cantidad de letras 'o':", cantidad_o)
    ```

- `join(lista)`: Concatena las cadenas de texto de la lista en una sola cadena utilizando la cadena como separador.

    ```python
    lista_colores = ["rojo", "verde", "azul"]
    # Une la lista en una cadena separada por comas
    cadena_colores = ",".join(lista_colores)

    print(cadena_colores)
    ```

- `startswith(cadena1, cadena2)`: Devuelve `True` si la cadena `cadena1` comienza con la subcadena `cadena2`, de lo contrario, devuelve `False`.

    ```python
    texto = "Hola, mundo!"
    if texto.startswith("Hola"):
        print("El texto comienza con 'Hola'")
    else:
        print("El texto no comienza con 'Hola'")
    ```

- `endswith(cadena1, cadena2)`: Devuelve `True` si la cadena `cadena1` termina con la subcadena `cadena2`, de lo contrario, devuelve `False`.

    ```python
    texto = "Este es un ejemplo de cadena"
    if texto.endswith("cadena"):
        print("La cadena termina con 'cadena'")
    else:
        print("La cadena no termina con 'cadena'")
    ```

- `lstrip(cadena)`: Elimina los espacios en blanco al inicio de la cadena de texto.

    ```python
    texto = "   Hola, mundo!"
    texto_sin_espacios_iniciales = texto.lstrip()
    print(texto_sin_espacios_iniciales)
    ```

- `rstrip(cadena)`: Elimina los espacios en blanco al final de la cadena de texto.

    ```python
    texto = "Hola, mundo!   "
    texto_sin_espacios_finales = texto.rstrip()
    print(texto_sin_espacios_finales)
    ```

- `isalpha(cadena)`: Devuelve `True` si todos los caracteres de la cadena de texto son letras, de lo contrario, devuelve `False`.

    ```python
    texto = "HolaMundo"
    if texto.isalpha():
        print("El texto contiene solo letras")
    else:
        print("El texto no contiene solo letras")
    ```


- `isdigit(cadena)`: Devuelve `True` si todos los caracteres de la cadena de texto son dígitos, de lo contrario, devuelve `False`.

    ```python
    cadena_digitos = "12345"
    cadena_letras = "abcde"

    print(cadena_digitos.isdigit())
    print(cadena_letras.isdigit())
    ```

- `isalnum(cadena)`: Devuelve `True` si todos los caracteres de la cadena de texto son letras o dígitos, de lo contrario, devuelve `False`.

    ```python
    cadena1 = "python3"
    print(cadena1.isalnum())    # Imprime True

    cadena2 = "Hola mundo"
    print(cadena2.isalnum())    # Imprime False

    cadena3 = "123@abc"
    print(cadena3.isalnum())    # Imprime False

    cadena4 = ""
    print(cadena4.isalnum())    # Imprime False
    ```

- `isspace(cadena)`: Devuelve `True` si todos los caracteres de la cadena de texto son espacios en blanco, de lo contrario, devuelve `False`.

    ```python
    cadena1 = "     \t\n"
    cadena2 = "Hola, mundo!"
    cadena3 "123"

    print(cadena1.isspace())    # Imprime True
    print(cadena2.isspace())    # Imprime False
    print(cadena3.isspace())    # Imprime False
    ```

## Secuencia de escape en cadena de texto

El escape de cadenas en Python es un mecanismo que se utiliza para representar caracteres especiales o secuencias de caracteres que no se interpretan literalmente dentro de una cadena de texto. Esto es útil para evitar confusiones o errores cuando se trabaja con cadenas que contienen caracteres que tienen un significado especial en el lenguaje de programación.

**¿Cuándo se necesita escapar una cadena?**

Se debe escapar una cadena en Python cuando contiene alguno de los siguientes caracteres:

- Comillas simples (`'`): Se utiliza para delimitar cadenas de texto, por lo que si se quiere incluir dentro de una cadena, hay que escaparla. 

- Comillas dobles (`"`): Al igual que las comillas simples, se utiliza para delimitar cadenas de texto, por lo que si se quiere incluir dentro de una cadena, hay que escaparla.

- Barra invertida (`\`): Se utiliza para escapar caracteres especiales, por lo que si se quiere incluir una barra invertida literalmente, hay que escaparla.

- Barra de carro (`\r`): Se utiliza para representar el retorno de carro, por lo que si se quiere incluir un retorno de carro literalmente, hay que escaparla.

- Salto de línea (`\n`): Se utiliza para representar el salto de línea, por lo que si se quiere incluir un salto de línea literalmente, hay que escaparla.

- Tabulación (`\t`): Se utiliza para representar la tabulación, por lo que si se quiere incluir una tabulación literalmente, hay que escaparla.

- Campana (`\a`): Se utiliza para representar la campana, por lo que si se quiere incluir una campana literalmente, hay que escaparla.

- Retroceso (`\b`): Se utiliza para representar el retroceso, por lo que si se quiere incluir un retroceso literalmente, hay que escaparla.

- Alimentación de formulario (`\f`): Se utiliza para representar la alimentación de formulario, por lo que si se quiere incluir una alimentación de formulario literalmente, hay que escaparla.

## [HAZ CLICK AQUÍ PARA IR A LOS EJERCICIOS](04_cadenas_texto.py)