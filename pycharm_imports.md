# imports python 
## Archivo main
### con sus imports

import utilerias as util
import suma as s
import resta as r
import division as d
import multi as m
import cuadrado as c

if __name__=="__main__":
    print("suma", s.suma(4,5))
    print("resta", r.resta(5,3))
    print("division", d.division(5,2))
    print("multiplicacion", m.multi(5,10))
    print("cuadrado", c.cuadrado(10))
    
    
## archivo suma
def suma(a:int, b:int)->int:

    return a + b

if __name__=="__main__":
    print(suma(4,5))

## archivo resta
def resta(a:int, b:int)->int:

    return a-b

if __name__=="__main__":
    print(resta(4,3))

## archivo multiplicacion 
def multi(a:int, b:int )->int:

    return a*b

if __name__=="__main__":
    print(multi(4,2))


## archivo division
def division(a:int, b:int)->float:


    return a/b

if __name__=="__main__":
    print(division(4,2))

## archivo cuadrado
def cuadrado(a:int)->int:

    return a*a


if __name__=="__main__":
   print(cuadrado(5))


## todos los archivos en uno solo
def suma(a:int, b:int)->int:

    return a + b
#-----------------------------------

def cuadrado(a:int)->int:

    return a*a
#-----------------------------------

def resta(a:int, b:int)->int:

    return a-b
#-----------------------------------

def division(a:int, b:int)->float:

    return a/b
#-----------------------------------

def multi(a:int, b:int )->int:

    return a*b

#-----------------------------------
if __name__=="__main__":
    print(suma(4,5))
    print(cuadrado(5))
    print(resta(4, 3))
    print(division(4, 2))
    print(multi(4, 2))
