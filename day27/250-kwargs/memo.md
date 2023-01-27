## **Intro of Unlimited Keywords Arguments (Optional)**

![Alt **kwargs](pic/01.jpg)

- 'kwargs' is a conventionally used variable name, sometimes just 'kw', but this name can be changed to suit your preference.

## **Usage of Kwargs**

> kwargs are actually dictionaries, so here are two common use cases.

### _for in loop_

![Alt usage 1: for in loop](pic/02.jpg)

### _get specific value from kwargs_

![Alt usage 2: get specific value in dict 'kwargs'](pic/03.jpg)

## **Reason Tkinter use lots of \*\*kw**

![Alt why Tkinter has lots of method/class using **kw](pic/04.jpg)

- TK is a completely different language from Python and uses almost all functions in the language when making components like Label, so only the Unlimited Keywords Arguments are suitable for this purpose.

## **Init Class with \*\*kw**

> We can also use Unlimited Keywords Arguments for initialization when designing the class, so that we can have more flexibility in initialization.

### _init(\*\*kw)_

![Alt use **kw to init class](pic/05.jpg)

### _lack of value_

![Alt when lack of keyword value](pic/06.jpg)

![Alt better way to get value from kw](pic/07.jpg)

- In fact, in this use case (Class initialization), .get() is almost always used and rarely [ ] is used.
