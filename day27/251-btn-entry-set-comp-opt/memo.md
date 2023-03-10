## **Set Option**

### _Checking documents_

![Alt three way to set option (doc)](pic/01.jpg)

### _Practice_

![Alt practice](pic/02.jpg)

## **Button component**

### _Checking documents for options_

> Instead of Python documents, Tcl/Tk documents will list all options.

![Alt check tcl/tk documents](pic/03.jpg)

### _Create Button component_

![Alt create button component](pic/04.jpg)

- Because all components are under the tkinter namespace, it is common to use "import tkinter as tk" or "from tkinter import \*" to reduce repetition of "tkinter".

### _Create function of button_

![Alt create function of button](pic/05.jpg)

### _Challenge: Change Label text when clicking button_

![Alt challenge: change label text when clicking button](pic/06.jpg)

![Alt solution](pic/07.jpg)

## **Entry component**

### _Create Entry component_

![Alt create Entry component](pic/08.jpg)

### _Narrowing Entry_

![Alt check Entry document to shrink its width](pic/09.jpg)

![Alt try it](pic/10.jpg)

### _Get value from Entry_

![Alt try to get value from Entry, check its document](pic/11.jpg)

![Alt check doc detail](pic/12.jpg)

![Alt use it but not work ideally](pic/13.jpg)

### _Fix the problem_

> The above "my_label.config(text=input.get())" should not be executed at the beginning, but should be triggered by an event, which we can achieve with Button.

![Alt fix  the problem](pic/14.jpg)

![Alt test it further](pic/15.jpg)
