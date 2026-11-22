[tkos.zero.txt](https://github.com/user-attachments/files/35233728/tkos.zero.txt)



import tkinter as tk
import webbrowser, platform, os
pencere = tk.Tk()
pencere.geometry("320x150")

tk.Button(pencere, text="google", command=lambda: webbrowser.open("google.com")).place(x=0, y=0)
tk.Button(pencere, text="youtube", command=lambda: webbrowser.open("youtube.com")).place(x=60, y=0)
tk.Button(pencere, text="sys", command=lambda: yazi.config(text=str(platform.uname())), bd=2, relief="raised").place(x=130, y=0)
tk.Button(pencere, text="usb", command=lambda: os.startfile("F:/")).place(x=180, y=0)

yazi = tk.Label(pencere, text="...", bd=2, relief="sunken", anchor="nw", justify="left", wraplength=300)
yazi.place(x=10, y=40, width=300, height=90)

pencere.mainloop()
