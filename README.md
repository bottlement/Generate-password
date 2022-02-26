# Generate-password
from tkinter import *  
top = Tk()  
top.geometry("400x260")  
name = Label(top, text = "Name").place(x = 30,y = 50)  
email = Label(top, text = "Email").place(x = 30, y = 90)  
password = Label(top, text = "Password").place(x = 30, y = 130)  
submit = Label(top, text = "Submit"). place (x = 80, y = 180)
e1 = Entry(top).place(x = 80, y = 50)  
e2 = Entry(top).place(x = 80, y = 90)  
e3 = Entry(top).place(x = 95, y = 130) 
#e4 = Entry (top).place(x = 100, y = 150) 
top.mainloop()
