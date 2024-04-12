# Expresiones Regulares (Regex)

Las expresiones regulares (también conocidas como regex o regexp) son patrones utilizados para encontrar una cierta secuencia de caracteres dentro de una cadena de texto. Son muy útiles para buscar, validar y manipular texto basado en patrones específicos.

## Metacaracteres

Los metacaracteres son caracteres con un significado especial en expresiones regulares. Algunos ejemplos son:

- `.` (C.T): coincidiria con "cat", "cot", "cut", etc.
- `^`: Indica el inicio de una cadena.
- `$`: Indica el final de una cadena.
- `*`: Representa cero o más repeticiones del elemento anterior.
- `+`: Representa una o más repeticiones del elemento anterior.
- `?`: Representa cero o una repetición del elemento anterior.
- `\`: Utilizado para escapar metacaracteres o para indicar secuencias especiales como `\d` (dígitos), `\w` (cualquier carácter alfanumérico), `\s` (espacio en blanco), entre otros.

## Clases de caracteres

Las clases de caracteres son conjuntos de caracteres que se pueden utilizar para representar un solo carácter dentro de una expresión regular. Por ejemplo:

- `[abc]`: Representa cualquier carácter que sea 'a', 'b' o 'c'.
- `[0-9]`: Representa cualquier dígito del 0 al 9.
- `[^abc]`: Representa cualquier carácter que no sea 'a', 'b' o 'c'.

## Agrupación y cuantificadores

Se utilizan paréntesis para agrupar expresiones y cuantificadores para especificar cuántas veces se puede repetir un patrón. Por ejemplo:

- `(abc)`: Representa la secuencia 'abc'.
- `(abc)+`: Representa una o más repeticiones de 'abc'.
- `(abc){2,4}`: Representa 'abc' repetido de 2 a 4 veces.

## Anclajes

Los anclajes son caracteres que indican posiciones específicas dentro de una cadena. Por ejemplo:

- `^`: Representa el inicio de una cadena.
- `$`: Representa el final de una cadena.

## Modificadores

Los modificadores son opcionales y se utilizan al final de una expresión regular para modificar su comportamiento. Algunos ejemplos son:

- `i`: Ignora mayúsculas y minúsculas.
- `g`: Realiza una búsqueda global (encuentra todas las coincidencias en lugar de detenerse en la primera).
- `m`: Habilita el modo multilinea.

Las expresiones regulares pueden ser muy poderosas pero también complicadas. La práctica y la comprensión de los conceptos básicos son clave para dominar su uso.
