# Python

_Notas from Python_


Para indicar donde empieza el programa:
```
if __name__ == '__main__':
    main()
```
Devuelve el tipo de la variable:
```
>>>type(2)
...<type 'int'>
```
Declarar un Parrafo:
```
paragraph = """Paragraph. It is	parrafo	
multiple lines."""
```
Aplicar variables a la salida en un string:
```
'${} pasos mexicanos son ${} pesos mexicanos'.format(ammount, result)
```
Palabra is para comprar si un valor es algo:
```
if variable is True	
```
El resultado es True  por que la letra a esta antes de la letra c:
```
if 'a' < 'c'
```
Para obtener las longuitudes del argumento:
```
len(string)	
```
Para obtener ayuda de una libreria:
```
help('math')
```

## Strings

Algunas operaciones con cadenas:
```
cadena.upper()		
cadena.lower()		
cadena.capitalize()		
cadena.find('u')		
cadena.replace("un","uno")		
cadena.strip()		
cadena.isdigit()		
cadena.isalpha()		
cadena.isalnum()		
cadena.split()		
cadena.split(",")		
```
## Excepciones

Lanzar un error similar a throw de Java:
```
raise Error("mensaje")
```

Estructura:
```
try:
   xxxxxx
except Error as error:
   xxxxxx
finally: 
   xxxxxx
```
Puede omitirse la clausula except, pero nunca puede estar solo try, por lo que hay que colocar finally:
```
try:
   xxxxxx
finally: 
   xxxxxx
```
## POO

Los dos guiones a la izquierda los convierten en privados tanto funciones como atributos:
```
def __atributo
def __funcion(self)
```
