# GUI-Application-with-Tkinter
A simple GUI application using Tkinter.
import tkinter as tk

def on_button_click():
    label.config(text="Hello, " + entry.get())

root = tk.Tk()
entry = tk.Entry(root)
button = tk.Button(root, text="Greet", command=on_button_click)
label = tk.Label(root, text="Enter your name:")

entry.pack()
button.pack()
label.pack()

root.mainloop()
