sw = True

def sumar():
    if opcion == 1:
        print("Operación de Suma")
        Num1 = int(input('Número 1: '))
        Num2 = int(input('Número 2: '))
        print(Num1 + Num2)

def restar():
   if opcion == 2:
        print("Operación de Resta")
        Num1 = int(input('Número 1: '))
        Num2 = int(input('Número 2: '))
        print(Num1 - Num2)

def multiplicar():
    if opcion == 3:
        print("Operación de Multiplicación")
        Num1 = int(input('Número 1: '))
        Num2 = int(input('Número 2: '))
        print(Num1 * Num2)

def dividir():
    if opcion == 4:
        print("Operación de División")
        Num1 = int(input('Número 1: '))
        Num2 = int(input('Número 2: '))
        print(Num1 / Num2)

def fin_del_programa():
    print('Programa Finalizado')
    global sw
    sw = False

def opcion_no_disponible():
    print('Opcion no disponible')

menu = '''
====Calculadora====
1.Sumar
2.Restar
3.Multiplicar
4.Dividir
5.Salir
'''

while sw:
    print(menu)
    opcion = int(input('Ingrese la opción: '))
    if opcion == 1:
        sumar()
    elif opcion == 2:
        restar()
    elif opcion == 3:
        multiplicar()
    elif opcion == 4:
        dividir()
    elif opcion == 5:
        fin_del_programa()
    else:
        opcion_no_disponible()