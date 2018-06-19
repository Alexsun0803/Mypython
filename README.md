# Mypython

TESTING 1

 def print_params_4(x, y, z=3, *pospar, **keypar): 
...     print(x, y, z) 
...     print(pospar) 
...     print(keypar) 
... 
>>> print_params_4(1, 2, 4, 5, 6, 7, foo=1, bar=2)
1 2 4
(5, 6, 7)
{'bar': 2, 'foo': 1}
>>> print_params_4(1, 2) 
1 2 3
()
{}



TESTING 2

 def hello_3(greeting='Hello', name='world'): 
...     print('{}, {}!'.format(greeting, name)) 
... 
>>> hello_3()
Hello, world!
>>> hello_3('Greetings')
Greetings, world!
>>> hello_3('Greetings', 'universe') 
Greetings, universe!
>>> hello_3(name='GGGGGGoood') 
Hello, GGGGGGoood!


