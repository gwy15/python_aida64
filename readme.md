# python_aida64

A python implementation of reading aida64 data via shared memory. Works on Windows only, as you would imagine.

## Usage
```Python
>>> import python_aida64
>>> from pprint import pprint
>>> pprint(python_aida64.getData())
{'fan': [{'id': 'FCPU', 'label': 'CPU', 'value': '906'},
         {'id': 'FCHA1', 'label': 'Chassis #1', 'value': '2601'}],
 'pwr': [{'id': 'PCPUPKG', 'label': 'CPU Package', 'value': '19.13'},
 [... more lines]
```
