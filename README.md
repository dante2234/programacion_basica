# Programación Básica.

----
## Curso de Python.
Python es un lenguaje de programación interpretado cuya filosofía hace hincapié en una sintaxis que favorezca un código legible. 
Se trata de un lenguaje de programación multiparadigma, ya que soporta orientación a objetos, programación imperativa y, en menor medida,
programación funcional.

----

## Python
para el curso de python se requerira el progama de anaconda python ya que este incluye las librerias necesarias sin nececidad de descargarlas aparte,
con la ventaja de que incluye programas que facilitaran la programacion como lo son spyder, y visual studio code
descargar [Anaconda Python]
(https://www.anaconda.com/distribution/)
### Operadores
DATOS BASICOS

En python los tipos de datos básicos se dividen en, números, como pueden ser : 3 entero (integer) ,1.75 punto flotante (float), 7+5j (complejos ó complex).

Para poder conocer el tipo de dato de una variable susaremos la instrucción "type()".

Otro tipo de dato basico en PYTHON son las cadenas de texto, por ejemplo, "Hola Mundo" (cadena de texto o string ó 'Hola Mundo' ó "Jenny's dog").

Como se puede notar a diferencia de muchos otros lenguajes en PYTHON no se declara el tipo de variable al crearla.

Para resumir en PYTHON se puede reprecentar números enteros, reales, y complejos. Los números enteros son aquellos números positívos o negatívos que no tienen desimales. En la mayor parte de las maquinas las variables enteras ("int") pueden almacrnar números de -2^31 a 2^31. En plataformas de 64 bites el rango es de -2^63 a 2^63.
Operadores:

		suma                    r=3+2
		resta	                r=4-7
            (guión) negación        r=-7
		multiplicación		r=2*6
		exponente		r=2**6
		división		r=3.5/2
		división entera		r=3.5//2
		modulo (residuo)	r=7%2

Un ejemplo de esto puede ser el siguiente:

    a=int(input('Incerta un numero '))   
    b=int(input('Incerta otro numero '))

    s=a+b   
    print('La suma es ' ,s)    
    r=b-a   
    print('La resta es ' ,r)    
    m=a*b   
    print('El producto es ' ,m)   
    d=a/b   
    print('El residuo es ' ,d)   
    dd=b/a
    print('El resultado es ' ,dd)    
    p=a**b   
    print('El resultado de "a" a la "b" es ' ,p)   
    import math    
    print('El logaritmo es ' ,math.log10(a))
![ejemplo en terminal](/imagenes/1.png)
