from tkinter import *

def error_absoluto(Xi1, Fi1):
    return abs(Xi1 - Fi1)
    
def calcular_error():
    x1 = float(cjtxt.get())  # x1
    f1 = float(cjtxt2.get())  # f1
    x2 = float(cjtxt3.get())  # x2
    f2 = float(cjtxt4.get())  # f2
    
    a1, a2 = x1 * f1, x2 * f2
    b1, b2 = f1 + f2, a1 + a2
    c1 = b2 / b1
    d1, d2 = c1 - x1, c1 - x2
    
    resultado.config(text=f"Error absoluto 1: {d1}\nError absoluto 2: {d2}")

v_principal = Tk()
v_principal.title("Metodos numericos")
v_principal.minsize(width=500, height=400)
v_principal.config(padx=25, pady=35)

eqt= Label(text="calculo de error absoluto",font=("ARIAL",14))
eqt.grid(column=0,row=0)

eqt1= Label(text="coloca tu medida",font=("ARIAL",14))
eqt1.grid(column=0,row=1)

cjtxt = Entry(width=20, font=("ARIAL",14))
cjtxt.grid(column=0,row=2)

eqt2= Label(text="coloca tu frecuencia",font=("ARIAL",14))
eqt2.grid(column=0,row=3)

cjtxt2 = Entry(width=20, font=("ARIAL",14))
cjtxt2.grid(column=0,row=4)

eqt3= Label(text="coloca tu medida",font=("ARIAL",14))
eqt3.grid(column=2,row=1)

cjtxt3 = Entry(width=20, font=("ARIAL",14))
cjtxt3.grid(column=2,row=2)

eqt4= Label(text="coloca tu frecuencia",font=("ARIAL",14))
eqt4.grid(column=2,row=3)

cjtxt4 = Entry(width=20, font=("ARIAL",14))
cjtxt4.grid(column=2,row=4)



btn1 = Button(text="calcular", font=("ARIAL",14), command=calcular_error)
btn1.grid(column=0, row=8)

resultado = Label(font=("ARIAL",14))
resultado.grid(column=0, row=9)

v_principal.mainloop()
