>>> a = dict(x=1, y=2)
>>> b = dict(y=1, z=2)

>>> c = a.copy()
>>> c
{'x': 1, 'y': 2}
>>> c.update(b)

>>> a
{'x': 1, 'y': 2}
>>> b
{'y': 1, 'z': 2}
>>> c
{'x': 1, 'y': 1, 'z': 2}

------------------------------------------------------------------------------

>>> a = dict(x=1, y=2)
>>> b = dict(y=1, z=2)

>>> a | b
{'x': 1, 'y': 1, 'z': 2}
