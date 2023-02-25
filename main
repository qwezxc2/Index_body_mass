from tkinter import * 
from tkinter import ttk  
import tkinter as index_body_mass 
import tkinter.filedialog as tfd
import tkinter.messagebox as tkm
import tkinter
window = tkinter.Tk()
window.title("Index body mass")
window.geometry("500x300")

tab_control = ttk.Notebook(window)  
tab1 = ttk.Frame(tab_control)  
tab2 = ttk.Frame(tab_control)
tab3 = ttk.Frame(tab_control)

def set_answer2(result2):
    text_answer2.delete(0, "end")
    text_answer2.insert(0, result2)

def set_answer(result):
    text_answer.delete(0, "end")
    text_answer.insert(0, result)

def get_num1():
    n = int(text_num1.get())
    return n

def get_num2():
    n = int(text_num2.get())
    return n

def imt():  
    text_num1 = get_num1()
    text_num2 = get_num2()
    result = int(text_num2/(text_num1/100)**2)
    set_answer(result)


label_num = tkinter.Label(tab1, text = "Hello, свой body mass index(BMI)!", bg = "white")
label_num.place(x = 80, y = 30)

label_num1 = tkinter.Label(tab1, text = "Enter your height in centimeters", bg = "white")
label_num1.place(x = 40, y = 80)

text_num1 = tkinter.Entry(tab1, width = 20, bg = "white")
text_num1.place(x = 60, y = 100)

label_num2 = tkinter.Label(tab1, text="Write your weight", bg = "white")
label_num2.place(x = 40, y = 160)

text_num2 = tkinter.Entry(tab1, width = 20, bg = "white")
text_num2.place(x = 60, y = 180)

label_num3 = tkinter.Label(tab1, text = "Your BMI = ", bg = "white")
label_num3.place(x = 260, y = 120)

button_imt = tkinter.Button(tab1, command = imt, text="Search BMI!",width = 10, height = 2, bg = "white")
button_imt.place(x = 240, y = 80)

text_answer = tkinter.Entry(tab1, width = 20, bg = "white")
text_answer.place(x = 340, y = 120)

label_num4 = tkinter.Label(tab1, text = "", bg = "white")
label_num4.place(x = 40, y = 160)


tab_control.add(tab1, text = 'BMI')  
tab_control.pack(expand = 1, fill = 'both')  

tab_control.add(tab2, text = 'What is it?')  
tab_control.pack(expand = 1, fill='both')  

lbl2 = Label(tab2, text='Body mass index.')  
lbl2.grid(column = 0, row = 0) 
lbl2 = Label(tab2, text = 'With this program, you can understand whether you lose weight, or vice versa gain weight.')  
lbl2.grid(column = 0, row = 1) 

tab_control.add(tab3, text = 'Table BMI')
tab_control.pack(expand = 1, fill = 'both')
lbl3 = Label(tab3, text = 'if your BMI less than 18, then you must be sure to eat')
lbl3.grid(column = 0, row = 0)
lbl3 = Label(tab3, text = 'if your BMI is more than 18.5, but less than 25, then you have normal weight')
lbl3.grid(column = 0, row = 1)
lbl3 = Label(tab3, text = 'If your BMI is more than 25, but less than 30, then you should lose some weight')
lbl3.grid(column = 0, row = 2)
lbl3 = Label(tab3, text = 'If your BMI is more than 33, then you urgently need to lose excess weight')
lbl3.grid(column = 0, row = 3)


text_answer2 = tkinter.Entry(tab1, width = 25, bg = "white")
text_answer2.place(x = 340, y = 75)




window.configure(bg = "white")

window.mainloop()
