# PEP 8 - Style Guidelines 
Author - Guido Van Rossum

## 1.Indetation
- Utilize 4 spaces per indentation level
- 4 space line rule is optional for continuous lines
- Spaces are the prefered indentation method to Tabs 
- Tabs Should be used exclusively to code pre indented with Tabs
- Mixing of Tabs and Spaces is dissallowed in python

## Maximum Line limit
- Limit all lines to 79 Character 
- All docstring and comments should be wrapped in 72 characters

## Line Breaks VS Binary Operators
- Line breaks should occur before binary operation
- Eg : sum = (value_1 
              + value_2)
    
## Blank lines
- Top level functions and classes should be surrounded by 2 blank lines
- subsidiary functions eg methods in classes should be separates by a blank line
- Use of functions sparingly in functions to indicate logical sections 

## Source File encoding
- Core python files should utilize UTF-8 encoding standard
- All identifiers i python standard library must use the ASCII-only identifier

## Imports
- Imports should be on Separate lines 
- EG : import os
       import pandas
    OR
       from subprocess import Popen, PIPE

## Module Level Dunder Names
- Module level dunders should be placed after the module docstring but before any import
- With the exception of the "from __future__ import"