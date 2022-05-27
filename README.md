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
## Listas

Dado que:
lista = [1,2,3,4,5,6]
>>>lista[1]
2
>>>lista.append(7)
[1,2,3,4,5,6,7]
>>>del lista[6]
[1,2,3,4,5,6]
>>>lista[3:] 
[4,5,6]
>>>lista[1:3]
[2,3]
>>>lista[1:6:2]
[2,4,6]
>>>lista[::-1]
[6,5,4,3,2,1]
>>>list('string')
['s','t','r','i','n','g']
>>> cadena = ''.join(['s','t','r','i','n','g']))
'string'
>>>sum([4,3,2,1])
10
Aplica la funcion a cada elemento de la lista
>>>map(str,[5,6,4])  
['6','5','4']

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
