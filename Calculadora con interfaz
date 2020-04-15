import tkinter as tk

root = tk.Tk()

Num1 = tk.StringVar()
Num2 = tk.StringVar()
resultado = tk.StringVar()

sw = False
def sumar():
        Suma = int(Num1.get())+int(Num2.get())
        Num1.set('')
        Num2.set('')
        return resultado.set(Suma)

def restar():
        Resta = int(Num1.get())-int(Num2.get())
        Num1.set('')
        Num2.set('')
        return resultado.set(Resta)

def multiplicar():
        Multiplicar = int(Num1.get())*int(Num2.get())
        Num1.set('')
        Num2.set('')
        return resultado.set(Multiplicar)

def dividir():
        Dividir = int(Num1.get())/int(Num2.get())
        Num1.set('')
        Num2.set('')
        return resultado.set(Dividir)

root.geometry('400x400')
root.title('Calculadora')
root.configure(bg="#448aff")

tk.Label(root, text='CALCULADORA', bg="#448aff", fg='white', font=('',20)).place(x=170, y=20)
#numero1
tk.Label(root, text='Número', bg="#448aff", fg='white', font=('',16)).place(x=20, y=100)
tk.Entry(root, justify='center', textvariable=Num1).place(x=140, y=105)

#numero2
tk.Label(root, text='Número', bg="#448aff", fg='white', font=('',16)).place(x=20, y=150)
tk.Entry(root, justify='center', textvariable= Num2).place(x=140, y=155)

#resultado
tk.Label(root, text='Resultado', bg="#448aff", fg='white', font=('',16)).place(x=20, y=200)
tk.Entry(root, justify='center', textvariable=resultado).place(x=140, y=205)

#Botones
tk.Button(root, text='Sumar', bd=0, command=sumar).place(x=300, y=100)
tk.Button(root, text='Restar', bd=0, command=restar).place(x=300, y= 130)
tk.Button(root, text='Multiplicar', bd=0, command=multiplicar).place(x=300, y=160)
tk.Button(root, text='Dividir', bd=0, command=dividir).place(x=300, y=190)
tk.Button(root, text='Salir', bd=0, command=root.destroy).place(x=190, y=360)

root.mainloop()

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