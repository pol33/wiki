
Saber si N libreria esta instalada
==================================

Como saber si N libreria esta instalada SIN ingresar al interprete de Python, funciona en la Bash de Linux.

::

   python -c 'import libreria'&&echo OK

Ejemplo:

::

   juan@maverick:~$ python -c 'import gtk'&&echo OK
   OK
   juan@maverick:~$ python -c 'import libreriaquenoestainstalada'&&echo OK
   Traceback (most recent call last):
     File "<string>", line 1, in <module>
   ImportError: No module named libreriaquenoestainstalada
   juan@maverick:~$

-------------------------



  CategoryRecetas_

