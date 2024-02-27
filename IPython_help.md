## **Accessing Documentation with ?** <br>
Every Python object contains a reference to a string called docstring, which contains a concise description of what the object does/means + how to use it.
- Help function can be used for printing out this info contained in the docstring, e.g., help(len) displays the docstring of the inbuilt help function inline or in a separate pop-up window.
- Instead of using the help function, IPython offers the ? character to print out the same thing as output of a command on the same terminal window,
- we can do this using len? and that will print out the docstring below this command; the output usually contains signature (if it's a function), docstring, and type.
