Naming convention
=================
All identifiers MUST use ASCII-only identifiers, and SHOULD use English words wherever feasible (in many cases, abbreviations and technical terms are used which aren't English). In addition, string literals and comments must also be in ASCII.

Naming style:
    - **modules** should have short, all-lowercase names, underscores can be used in the module name if it improves readability
    - python **packages** should also have short, all-lowercase names, although the use of underscores is discouraged
    - **class names** use the CapWords convention
    - **function and method names** should be lowercase, with words separated by underscores
    - **exceptions** should be classes, use the CapWords convention
    - **variable names** should have all-lowercase names, underscores can be used in the module name if it improves readability (global_var_name, instance_var_name, function_parameter_name, local_var_name)
    - **global constants** are usually defined on a module level and written in all capital letters with underscores separating words

Special names:
    - always use *self* for the first argument to instance methods
    - always use *cls* for the first argument to class methods
    - prepending a single underscore (_) has some support for protecting module variables and functions (not included with import * from)
    - prepending a double underscore (__) to an instance variable or method effectively serves to make the variable or method private to its class
    - for exceptions you should use the suffix "Error" (if the exception actually is an error)

Names to Avoid:
    - avoid *global variables*
    - single character names except for counters or iterators
    - dashes (-) in any package/module name
    - __double_leading_and_trailing_underscore__ names (reserved by Python)
    - do not use Hungarian notation
    - avoid numerals in names

Names Abbreviation:
    - abbreviate each variable name to between 8 to 20 charracters
    - use standard abbreviations (the ones in common use, which are listed in a dictionary)
    - use every significant word in the name, up to a maximum of three words
    - remove useless suffixes — ing, ed, and so on
    - don't abbreviate by removing one character from a word
    - always use the same abbreviation
    - Read more: *Code Complete 2ed: 11.6 Creating Short Names That Are Readable*

Used:
    - PEP 8 -- Style Guide for Python Code: http://www.python.org/dev/peps/pep-0008/
    - Google Python Style Guide: http://google-styleguide.googlecode.com/svn/trunk/pyguide.html
    - Django. Coding style: https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/coding-style/
    - Code Complete 2ed by Steve McConnell 2004
