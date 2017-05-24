=========
The Begin
=========

In Python the variables are dynamically typed, meaning that Python identifies the kind of 
variable by itself. Here is a list of the most basic types: 

- Integer
- Float
- complex 
- NoneType
- Boolean
- String
- List
- Tuples 
- Dictionaries

Python supports arithmetic operations, and they are calculated using:

- \+ for addition
- \- for subtraction 
- / for division
- \* for multiplication
- ** for exponentiation

The comparison operations are possible too; here is the operators: 

- > for greater than
- < for less than
- >= for grater than or equal to 
- <= for less than or equal to 
- != for not equal 
- == for equal


Types
-----

The numbers are usually represented by the types below.

Integer 
~~~~~~~
.. code-block:: python

   >>> a = 11
   >>> type(a)
   <type 'int'>


Float
~~~~~
.. code-block:: python

   >>> a = 11.
   >>> type(a)
   <type 'float'>

Complex
~~~~~~~
.. code-block:: python

   >>>  a = 11 + 3j  
   >>> type(a)
   <type 'complex'>


All the Arithmetic operations works well for that three types, and the comparison between numbers
possible too (by definition the comparison between complex is not possible). Below, there is a few
examples.

.. code-block:: python

   >>> a = 3
   >>> b = 11
   >>> c = 3.
   >>> d = 10 + 3j
   >>>
   >>> b/a
   3
   >>> 
   >>> b/c
   3.6666666666666665
   >>>
   >>> a == c
   True
   >>>
   >>> d.conjugate()
   (10-3j)
   >>>
   >>> e = a*b
   >>> 9.0
   >>> 

There is two special types
~~~~~~~~~~~~~~~~~~~~~~~~~~
NoneType
~~~~~~~~
.. code-block:: python

   >>> a = None
   >>> type(a)
   <type 'NoneType'>

Boolean
~~~~~~~
.. code-block:: python

   >>> a = False
   >>> b = True
   >>> 
   >>> type(a)
   <type 'bool'>
   >>> type(b)
   <type 'bool'>


Other types
~~~~~~~~~~~

String
~~~~~~

Strings are the objects used to work with text, and those are sequence. 

.. code-block:: python

   >>> a = 'beatriz'
   >>> type(a)
   <type 'str'>

At this point, it is useful to introduce the function *dir()*.

.. code-block:: python
   
   >>> dir(a)
   ['__add__', '__class__', '__contains__', '__delattr__', '__doc__', '__eq__',
    '__format__', '__ge__', '__getattribute__', '__getitem__', '__getnewargs__',
    '__getslice__', '__gt__', '__hash__', '__init__', '__le__', '__len__', '__lt__',
    '__mod__', '__mul__', '__ne__', '__new__', '__reduce__', '__reduce_ex__',
    '__repr__', '__rmod__', '__rmul__', '__setattr__', '__sizeof__', '__str__',
    '__subclasshook__', '_formatter_field_name_split', '_formatter_parser', 'capitalize',
    'center', 'count', 'decode', 'encode', 'endswith', 'expandtabs', 'find', 'format',
    'index', 'isalnum', 'isalpha', 'isdigit', 'islower', 'isspace', 'istitle', 'isupper', 
    'join', 'ljust', 'lower', 'lstrip', 'partition', 'replace', 'rfind', 'rindex', 'rjust',
    'rpartition', 'rsplit', 'rstrip', 'split', 'splitlines', 'startswith', 'strip',
    'swapcase', 'title', 'translate', 'upper', 'zfill']
   >>> 
   >>> a.capitalize()
   'Beatriz'
   >>> 
   >>> b = 'paula'
   >>> a.capitalize() + b
   'Beatrizpaula'
   >>>
   >>> a.capitalize() + b.capitalize()
   'BeatrizPaula'
   >>>
   >>> a.capitalize() * 2
   'BeatrizBeatriz'
   >>> 
   >>> a.split('a')
   ['be', 'triz']
   >>>
   >>> a.replace('triz','r')
   'bear'
   >>> 


List
~~~~

List are sequence of things.

.. code-block:: python

   >>> a = [1, 2, 3, 'car', 'cptec', 'alunos']
   >>> type(a)
   <type 'list'>

Some operations with list

.. code-block:: python

   >>> a = [1, 2, 3, 'car', 'cptec', 'alunos']
   >>> b = ['agua', 4, '5', 'fogo']
   >>>
   >>> c = a + b
   >>> c
   [1, 2, 3, 'car', 'cptec', 'alunos', 'agua', 4, '5', 'fogo']
   >>>
   >>> c.sort()
   >>> c
   [1, 2, 3, 4, '5', 'agua', 'alunos', 'car', 'cptec', 'fogo']
   >>>
   >>> c.reverse()
   >>> c
   ['fogo', 'cptec', 'car', 'alunos', 'agua', '5', 4, 3, 2, 1]
   >>>
   >>> c.remove('alunos')
   >>> c
   ['fogo', 'cptec', 'car', 'agua', '5', 4, 3, 2, 1]
   >>>
   >>> a = 'meteorologia'
   >>>
   >>> a[5]
   'r'
   >>> a[-4]
   'o'
   >>> a[0:7]
   'meteoro'
   >>> a[-12:-5]
   'meteoro'
   >>> a[7:]
   'logia'
   >>> a[-5:]
   'logia'
   >>> a[0::2]
   'mtoooi'


Tuples
~~~~~~

Tuples are sequence, but they are immutable.

.. code-block:: python

   >>> a = ('water', 'fire', 4)
   >>> type(a)
   <type 'tuple'>

Some operations with tuples.

.. code-block:: python

   >>> a = ('water', 'fire', 4)
   >>>
   >>> a[1]
   'fire'
   >>> a[1] = 2
   Traceback (most recent call last):
     File "<stdin>", line 1, in <module>
   TypeError: 'tuple' object does not support item assignment
   >>>
   >>> c, d, f = a
   >>> c
   'water'
   >>> d
   'fire'
   >>> f
   4
   >>> 

Dictionaries
~~~~~~~~~~~~

Dictionaries are collections of elements, but it is referenced by keys.

.. code-block:: python

   >>> student = {'name':'Jose Dias', 'course':'python', 'day': 1 }
   >>> type(student)
   <type 'dict'>


.. code-block:: python

   >>> student = {'name':'Jose Dias', 'course':'python', 'day': 1 }





Exercises  
---------


