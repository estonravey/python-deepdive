Day 1:
# Python Type Hierarcy

## Numbers
- integral
    - integers
    - booleans

- non integral
    - Floats (c doubles)
    - Comples (have a real and imaginary component)
    - Decimals
    - Fractions (rational numbers)

- Collections

- sequences:
    - Mutable
        Lists

    - Immutable
        Tuples
        Strings

- Sets
    - Mutable
        Sets
    - Immutable
        Frozen sets

- Mappings
    - Dicitonaries

- Callables
    - User-defined functions
    - Generators
    - Classes
    - Instance Methods
    - Class Instances ( __call__())
    - Built-in Functions (eg. len(), open())
    - Build-in Methods (eg. my)lis.append(x)

- Singletons
    - None
    - NotImplemented


# Identifiers:
- case sensitive 

## MUST
- start with _ or letter [a-zA-Z]
- followed by any numbrer of underscores or letters or digits
- cannot start an identifier with a digit
- cannot be reserved words:
    none
    true
    if else
    for while def lambda global nonlocal return yield
    del in is assert class

## CONVENTIONS
_my_var
- single underscore: this is a private object

from module import *
- python will not import _my_var

__my_var
- name mangling (oop)
- changles variable name for inheritance chains
- called "dunder"

__my_var__
- double underscore on both
- system defined names
- special meaning for interpreter
- stick to predefined ones
    __init__
    - initialize a class

## Other Naming Conventions
Packages    short, all lower case, no underscores
    - utilities

Modules     short, all lower case, can have underscores
    - db_utils

Classes     CapWOrds (upper cammel case)
    - BankAccount

Functions   lowercase, underscore (snake case)
    - open_account

Varialbes   lower case, snake case
    - account_id

Constants   all upper, underscore
    - MIN_APR

