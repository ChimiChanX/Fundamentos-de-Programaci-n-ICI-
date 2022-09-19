#  programas echos en clase
## Jupyter 
### interpolacion de cadenas 
name = "alex"
edad = 18
print ( "hola", name, "tienes ", edad, "años" )

### fstrings
mensaje= (f"hola {name}, tienes {edad} años")
mensaje

### prints

print(mensaje)

print(f"hola {name}, tienes {edad} años")


### funcion saludo 

def saludo():
    print("hola mundo")
    
mi_funcion=saludo() #asignando la funcion    

### llamada a la funcion 

saludo()

print(mi_funcion)

def saludo2():
    return "HOLA MUNDO!!"
    
mi_funcion2= saludo2

### suma de dos variables

a=5
b=10
res=f"la suma de {a}+{b}={a+b}"
print(res)

def suma(a,b):
    return a+b
    
res=f"la suma de {a}+{b}={suma(a,b)}"


print(res)


lista=["uno", "dos", "tres"]
msg_numeros=f"numeros: {lista}"
print(msg_numeros)


tuplas_numeros=("uno", "dos", "tres")
msg_numeros=f"numeros: {tuplas_numeros}"
print(msg_numeros)


set_numeros={"uno","dos","tres","tres"}
print(set_numeros)


dict_numeros={"1": "uno", "2": "dos", "3": "tres"}
msg_dict_numeros = f"numeros: {dict_numeros}"
print(msg_dict_numeros)


dos=f"numero:{dict_numeros['2']}"
print(dos)

# Escriba una funcion que mediante fstrings retorne el mensaje "Hola <nombre> tienes <edad> años".
# Los argumentos de la funcion si: año actual, año de nacimiento y nombre

a=21
b=2001
c="Luis Fernando"
def todo(a,b,c):
    return(todo)


todo=f"Hola, tu nombre es: {c}, naciste en {b}, tienes {a} años"
print(todo)




num_materia=["No. ",1,2,3,4]
name_materia=["Materia","Estructura de datos","Ecuaciones diferenciales","Programacion funcional","Metodos numericos"]
name_profesor=["Profesor","Soto","Eli","Walter","Edgar"]              
print (f"{num_materia[0]:^5}{name_materia[0]:^30}{name_profesor[0]:<6}")
for i in range (1,5):
    print(f"{num_materia[i]:^5}{name_materia[i]:<30}{name_profesor[i]:<6}")
alumnos=["Jose","Miguel","Orlando","Jan","Dani"]
name_materia=[6,8,6,8,7]
name_materia2=[8,9,10,8,9]
name_materia3=[8,8,7,6,9]
name_materia4=[9,9,9,9,10]

encabezado=["Nombre","Programacion funcional","Metodos numericos","Estructura de datos","Ingles"]

def reporte (fmt):
    print(f"{encabezado[0]:^{fmt}}{encabezado[1]:^{fmt}}{encabezado[2]:^{fmt}}{encabezado[3]:^{fmt}}{encabezado[4]:^{fmt}}")
    for i in range (5):
          print(f"{alumnos[i]:^{fmt}}{name_materia[i]:^{fmt}}{name_materia2[i]:^{fmt}}{name_materia3[i]:^{fmt}}{name_materia4[i]:*^{fmt}}")
reporte(20)
alumnos=["Jose","Miguel","jason","Jan","Dani"]
name_materia=[6,8,6,8,7]
name_materia2=[8,9,10,8,9]
name_materia3=[8,8,7,6,9]
name_materia4=[9,9,9,9,10]

encabezado=["Nombre","Programacion funcional","Metodos numericos","Estructura de datos","Ingles"]

def reporte (fmt):
    print(f"{encabezado[0]:^{fmt}}{encabezado[1]:^{fmt}}{encabezado[2]:^{fmt}}{encabezado[3]:^{fmt}}{encabezado[4]:^{fmt}}")
    for i in range (5):
          print(f"{alumnes[i]:^{fmt}}{name_materia[i]:^{fmt}}{name_materia2[i]:^{fmt}}{name_materia3[i]:^{fmt}}{name_materia4[i]:^{fmt}}")
reporte(20)

