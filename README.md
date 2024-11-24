# APUNTES PYTHON 

## Zen de python : 

Beautiflul if better than ugly

Simple is better than complex

Complex is betther than complicated

Readability counts.

There should be one-- and preferably only one --obvious way to do it.

Now is better than never.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------

## Variables y tipos de datos simples

- Los nombres de variable solo pueden contener letras, números y guiones bajos

- Una variable hace referencia a un valor determinado

- str = cadena de carácteres / strings

- Las comillas triples permiten crear cadenas que ocupan varias lineas. Esto es útil para definir textos con saltos de lineas y preservando los espacios

- Si dos cadenas literales aparecen en una misma línea separada por espacios en blanco, se concatenan

- el constructor srt convierte cualquier tipo de dato en una cadena . (cadena = str(numero))

### USO DEL FORMAT

- En el interior de la cadena podemos usar {} como marcador de los argumentos

Hola, soy {} y tengo {} años .format("Sergio", 20)

- (utilizamos el key-value para acceder al valor del argumento)


mensaje = "Hola, tengo {edad} años y me llamo {nombre}".format(nombre="Rivas", edad=37)

### USO DE F-STRINGS

- A partir de la versión 3.6 se introdujo f-Strings. (formateo literal de cadenas) Solo tienes que especificar el nombre de las variables dentro de las llaves {}

mensaje = f"Hola soy {Sergio} y tentgo {20} años

- Pueden evaluar expresiones válidas

print(f"El producto de {n1} y {n2} es {n1 * n2}

### Métodos para trabajar con strings en Pyhton

- capitalize() --> devuelve la primera letra en mayúscula

- lower() --> confierte todos los carácteres en minúscula

- upper() --> convierte todos los carácteres en mayúscula

- swapcase() --> convierte los caracteres con mayúsucla en minuscula y viceversa

- count() --> te permite contar las veces que otra cadena se encuentra dentro de la primera


-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## OPERADORES

- operadores aritmeticos : 

 | + | - | * | / | // | & | ** |

- operadores de asignación :

| = | += | -= | *= | /= | //= | %= | **= |




  
