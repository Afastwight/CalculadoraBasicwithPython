def suma(a,b):
    return a + b
def resta(a,b):
    return a - b 
def multiplicacion(a,b):
    return a * b
def division(a,b):
    return a / b

Estudiante = str(input("Nombre del Estudiante: "))
a = int(input("Ingrese primer numero: "))
b = int(input("Ingrese segundo numero: "))
opcion = int(input("Ingrese la opcion que desee que la calculadora utilize para resolver. 1.- Suma 2.-Resta 3.- Multiplicacion 4.- Division: "))

if opcion == 1:
    resultado = suma(a,b)
    print(f"{Estudiante} el resultado es : {resultado}")
if opcion == 2:
    resultado = resta(a,b)
    print(f"{Estudiante} el resultado es : {resultado}")
if opcion == 3:
    resultado = multiplicacion(a,b)
    print(f"{Estudiante} el resultado es : {resultado}")
if opcion == 4:
    resultado = division(a,b)
    print(f"{Estudiante} el resultado es : {resultado}")


