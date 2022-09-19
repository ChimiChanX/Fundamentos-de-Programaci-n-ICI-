# VS code
## listas

mi_lista = [1,2,3,4]
print(mi_lista)
lista_vacia= []
print(lista_vacia)

mi_lista2=[1,"hola", True,3.5,[1,2,3],(1,2,3),{4,5,6}]
print(mi_lista2)


print(len(mi_lista2))
print(f"Mi lista: {mi_lista}")
print(f"No. de elementos: {len(mi_lista)}")
print(f"Primer elemento: {mi_lista[-1]},{mi_lista[-2]},{mi_lista[-3]},{mi_lista[-4]}")

print(mi_lista[1:-1])
print(mi_lista[0:3])
print(mi_lista[0:])
print(mi_lista[:])


#modificar los datos de mi lista
mi_lista[2]="tres"
print(mi_lista)

# insertar la lista [5,"seis",7,8] al final de mi_lista

mi_lista[len(mi_lista):]=[5,"seis",7,8]
print(mi_lista)

# slices

mi_lista=[1,2,3,4]
mi_lista.append("cinco")
print(mi_lista)

ml=[]
for i in range(1,5):
    ml.append(i)

# ml.append([6,7,8])
#print(ml)
ml.extend([6,7,8])
print(ml)
ml.insert(4,"5")
print(ml)

del ml[5]
print(ml)

ml.remove('5') 
print(ml)

ml.reverse()
print(ml)
print("------------")

ld=[5,4,6,7,8,2,3,4,5,6,7]
print(f"Desordenado: {ld}")
ld.sort()
print(f"Ordenado: {ld}") 

ld=[[5,4,6],[7,8,2],[3,4,5],[1,6,7]]
print(f"Desordenado: {ld}")
ld.sort()
print(f"Ordenado: {ld}") 

mi_lista = [1,2,3,4]
print(mi_lista)
lista_vacia = []
print(lista_vacia)

mi_lista2=[1,"hola",True,[1,2,3], (1,2,3),{4,5,6}]
print(mi_lista2)

print(len(mi_lista2))
print(f"mi lista: {mi_lista}")

print(f"Numero de elementos: {len(mi_lista)}")
print(f"Primer elemento: {mi_lista[0]}")


# programa 
## Escribe una funcion que reciba como argumentos t, n.  Donde t es el limite de tablas de multiplicar que se desean obtener y m hasta que valor de las tablas se desea. todas empiezan desde 1

t=int 
n=int 

got=1
t=int(input("ingresa el numero:  "))

gon=1
n=int(input("marca cuantas veces:  "))

def ops(t,n):
    for num1 in range (got,t+1):
        print(f"multiplicacion numero : {num1}:")
        for num2 in range (gon, n+1):
            print(f"{num1} X {num2} = {num1*num2}")
        print()

ops(t,n)
