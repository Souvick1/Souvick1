import tkinter as tk
import webbrowser

def open_github():
    webbrowser.open("https://github.com/Souvick1")

root = tk.Tk()
root.title("Visit My GitHub")
root.geometry("300x120")

label = tk.Label(root, text="Click below to visit my GitHub!", font=("Helvetica", 12))
label.pack(pady=10)

button = tk.Button(root, text="Go to GitHub", command=open_github, bg="black", fg="white")
button.pack()

root.mainloop()
