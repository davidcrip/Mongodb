# Json VS Bson


```sh -- JSON --
# Ventajas de JSON
- Amigable
- Se puede leer
- Es un formato muy usado

# Desventajas de JSON
- Basado en texto
- Consume mucho espacio
- Es limitado: string, boolean, number, arrays
```


```sh -- BSON --
# Ventajas de BSON
- Representación binaria de JSON
- No consume espacio
- Alto rendimiento
- Tipos de datos: +, date, raw binary, integer, long, float

# Desventajas de BSON
- No es estándar
- Es un formato para la máquina

```



```sh
# MongoDB soporta muchos tipos de datos. Algunos de ellos son:

String: este es el tipo de datos más utilizado para almacenar los datos. La cadena en MongoDB debe ser válida para UTF-8.

Integer: este tipo se utiliza para almacenar un valor numérico. El número entero puede ser de 32 o 64 bits, dependiendo de su servidor.

Boolean: este tipo se utiliza para almacenar un valor booleano (verdadero / falso).

Double: este tipo se utiliza para almacenar valores de punto flotante.
Min / Max: este tipo se usa para comparar un valor con los elementos BSON más bajos y más altos.

Arrays: este tipo se usa para almacenar arrays o listas o múltiples valores en una clave.

Timestamp: Marca de hora. Esto puede ser útil para grabar cuando un documento ha sido modificado o agregado.

Object: este tipo de datos se utiliza para documentos incrustados.

Null: este tipo se utiliza para almacenar un valor nulo.

Symbol: este tipo de datos se utiliza de forma idéntica a una cadena; sin embargo, generalmente se reserva para idiomas que usan un tipo de símbolo específico.

Date: este tipo de datos se utiliza para almacenar la fecha u hora actual en formato de hora UNIX. Puede especificar su propia fecha y hora creando el objeto de Fecha y día, mes, año que pasa.

ObjectId: este tipo de datos se utiliza para almacenar la ID del documento.

Binary: este tipo de datos se utiliza para almacenar datos binarios.

Code: este tipo de datos se utiliza para almacenar el código JavaScript en el documento.

Regular Expression: este tipo de datos se utiliza para almacenar expresiones regulares.


```
