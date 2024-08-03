# Variables

## ¿Qué es una variable?

En el ámbito de la programación, una variable se define como un identificador asociado a un espacio de memoria donde se almacena un valor. Este valor puede ser modificado a lo largo de la ejecución de un programa. En Python, las variables no requieren una declaración explícita de tipo, ya que el interprete infiere el tipo de dato en tiempo de ejecución.

**Declaración y Asignación**

Para declarar una variable en Python, simplemente se asigna un valor a un identificador. Por ejemplo:

```python
nombre_variable = valor
```

**Ejemplo**:

```python
edad = 35 # Variable de tipo entero (int)
nombre = "Ana" # Variable de tipo cadena (str)
es_mayor_de_edad = True # Variable de tipo booleano (bool)
```

### Buenas prácticas para la declaración de variables en Python

La forma en que declaremos y utilizamos las variables en Python influyen directamente en la legibilidad, mantenibilidad y eficiencia de nuestro código. Aquí te presento algunas recomendaciones para la declaración de variables en Python:

**Nomenclatura significativa**: 

- Nombres descriptivos: Los nombres de las variables deben reflejar el propósito de los datos que almacenan. Por ejemplo, en lugar de `x`, usar `nombre_usuario`.

- Evitar nombres ambiguos: No utilices nombres demasiados cortos o genéricos que puedan confundir.

- Tipos de datos correctos: Asegúrate de que el nombre de la variable refleje el tipo de dato que almacena.

- Inicialización: Siempre inicializa las variables antes de utilizarlas.

- Documentación: Añade comentarios que expliquen el propósito de la variable.

**Convenciones de escritura de variables**

- **`Camel Case`**: Se utiliza para nombrar clases, métodos y funciones. La primera letra de cada palabra, excepto la primera, se escribe en mayúscula. Por ejemplo, `nombreUsuario`, `fechaNacimiento`.

- **`Pascal Case`**: Se utiliza para nombrar clases. La primera letra de cada palabra se escribe en mayúscula. Por ejemplo, `NombreUsuario`, `FechaNacimiento`.

- **`Snake Case`**: Se utiliza para nombrar variables y funciones. Las palabras se separan por guiones bajos. Por ejemplo, `nombre_usuario`, `fecha_nacimiento`.

### Ejercicios

1. Asigna un valor numérico a una variable y muestra su valor en la consola.

2. Asigna un valor de tipo cadena a una variable y muestra su valor en la consola.

3. Asigna un valor booleano a una variable y muestra su valor en la consola.