## **Accessing Documentation with ?** <br>
Every Python object contains a reference to a string called docstring, which contains a concise description of what the object does/means + how to use it.
- Help function can be used for printing out this info contained in the docstring, e.g., help(len) displays the docstring of the inbuilt help function inline or in a separate pop-up window.
- Instead of using the help function, IPython offers the ? character to print out the same thing as output of a command on the same terminal window,
- we can do this using len? and that will print out the docstring below this command; the output usually contains signature (if it's a function), docstring, and type.
- It works for object methods, objects themselves, or even for functions that we create.
- For adding a docstring to our custom functions, we can use the Python triple quotes as it supports multiline strings to create a string literal at the beginning of the function.
- We can exit from IPython using the exit function. Just type exit.


## **Accessing Source Code with ??** <br>
square?? gives the signature and source code of the square function.
- If a function is implemented in a language other than Python, like C, no source code is displayed.
- In such cases the output of ? is same as ??
- This happens with many of Python's built-in objects and types, like the len function.

## **Exploring Modules with Tab Completion** <br>
To see the various attributes and methods associated with a python object, we can use Tab after the period . symbol
- L = [1, 2, 3] is a list. If we write L.<TAB> we get a list of available attributes of the list object.
- We can type out few characters to match the ones we want.
- Most of the options we get come from Python's special double-underscore methods called dunder methods.
- Tab completion can also be used while importing libraries, e.g., from itertools import co<TAB> shows combinations(), compress(), combinations_with_replacement(), count(), etc.
- We can also use it like: import <TAB> or import h<TAB>

## **Wildcard Matching** <br>
Tab can be useful when we are aware of the initial few characters, but if not:
- We can use the * for wildcard matching, for anywhere in the name, beginning, middle, or end.
- *Warning? gives: 
  - BytesWarning
  - DeprecationWarning
  - EncodingWarning
  - FutureWarning
  - ImportWarning
  - PendingDeprecationWarning
  - ResourceWarning
  - RuntimeWarning
  - SyntaxWarning
  - UnicodeWarning
  - UserWarning
  - Warning
- str.*find*? gives:
  - str.find
  - str.rfind
- Quite useful for finding a command when learning a new package or reacquantign with a familiar one.

## **Keyboard Shortcuts in IPython Shell** <br>
4 major types:
- Navigation Shortcuts:
  - ctrl+a: move cursor to beginning of line
  - ctrl+e: move cursor to end of line
  - ctrl+b/left arrow key: move cursor back one character
  - ctrl-f/right arrow key: move cursor forward one character
- Text Entry Shortcuts:
  - ctrl+d: delete next character in line
  - ctrl+k: cut text from cursor to the end of line
  - ctrl+u: cut text from beginning of line to cursor
  - ctrl+y: yank/paste text that was previously cut
  - ctrl+t: transpose/switch previous two characters
- Command History Shortcuts: Beyond the current IPython session, your entire command history is stored in a SQLite database in your IPython profile directory.
  - ctrl+p/up arrow key: access previous command in history
  - ctrl+n/down arrow key: access next command in history
  - ctrl+r: reverse-search through command history
- Misc. Shortcuts:
  - ctrl+l: clear terminal session
  - ctrl+c: interrupt current python command, useful when you inadverdently start a very long-running job.
  - ctrl+d: exit ipython session
  
