# Namelist Reader in Python

This is a class to read Fortran-namelist in Python.
This is tested only on Python 3.7.7 and Python 3.9.6, however, will be able to be used in various Python3 versions because this class does not import any other modules.

## Usage
Import the class by `from namelist import namelist`.
Then, read a existing namelist by `nml=namelist.read(filename)`.
The returned parameter is `dict` type.
The names of the outer nest is the namelist name, and the inner one is the name of the parameters.

## Assumed Inputs
`int`, `float`, `int-array`, `float-array`, `bool`, and `str` are available for the parameter types.


