MTK (ModernTkinter)
MTK is a modernized version of CustomTkinter that provides a set of sleek and customizable widgets for Python GUI applications using Tkinter. :)

ModernTkinter -- The Modern Framework

MTK (ModernTkinter) is a modern version of Tkinter designed to bring contemporary features and stylish widgets to your Python GUI projects.

Features
ModernTabview: A tab view widget with rounded tabs and custom colors.
ModernProgressBar: A progress bar widget with a modern design and rounded corners.
ModernSlider: A customizable slider with a modern look and feel.
ModernButtons: Sleek, customizable, and rounded buttons for a modern UI.
ModernEntry: A stylish and rounded text input field for a smooth user experience.
ModernFrames: Clean and modern frames with rounded corners to organize content.
And much more! 😎

Installation
You can easily install MTK via pip:

bash
Copiar
Editar
pip install moderntkinter
Usage
Here’s an example of how to use MTK in your Python project:

python
Copiar
Editar
import moderntkinter as mtk
import tkinter as tk

# Create the main window
root = tk.Tk()
root.title("ModernTkinter Example")

# Create a ModernButton
button = mtk.ModernButton(root, text="Click Me!", command=lambda: print("Button Clicked"))
button.pack(pady=20)

# Run the application
root.mainloop()
PyPI
You can find MTK on PyPI and install it via pip:

https://pypi.org/project/moderntkinter/

License
This project is licensed under the MIT License.
