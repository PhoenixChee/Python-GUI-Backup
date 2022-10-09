# Python-GUI

I use TkInter as it is the beginner friendly and easy to program GUIs. I have research many other methods to program python GUI such as PyQT6 or Kivy and came to a conclusion that they are really not worth my time to learn during my FYP due to their steep learning curve. The best approach is to use TkInter if I really want to get this GUI done as quickly as possible. I use a theme called the Sun Valley, made by <<this person>> which transform TkInter ugly look into a modern one. Sun Valley is one of the best modern looking themes for TkInter that makes your GUI look great.

In this repository, I will guide you through how I program the TkInter GUI.

## Getting Started

For beginners, 

### Dependencies

These are the packages I use to program the GUI

* Pillow, OpenCV Python, sv-ttk, 

### GUI Structure

In the program, I have created a notebook, and inside the notebook it contains 3 Tabs laballed Home, Graph, Cam.

### GUI Home Tab

In this Home tab, I have layout 7 frames: MenuBar, Odrive(Box 1), Motors (Box 2), Dashboard (Box 3), Battery (Box 4), Speed & Steeting (Box 5) and Controls (Box 6).

Menubar contains the 2 child frames: add_widgets_left (A), add_widgets_right (B). I contraints A to the left, and B to the right.
Inside A, there is 2 switch buttons
