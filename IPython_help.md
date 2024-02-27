## **Accessing Documentation with ?** <br>
Every Python object contains a reference to a string called docstring, which contains a concise description of what the object does/means + how to use it.
- Help function can be used for printing out this info contained in the docstring, e.g., help(len) displays the docstring of the inbuilt help function inline or in a separate pop-up window.
- Instead of using the help function, IPython offers the ? character to print out the same thing as output of a command on the same terminal window,
- we can do this using len? and that will print out the docstring below this command; the output usually contains signature (if it's a function), docstring, and type.
- It works for object methods, objects themselves, or even for functions that we create.
- For adding a docstring to our custom functions, we can use the Python triple quotes as it supports multiline strings to create a string literal at the beginning of the function.
- We can exit from IPython using the exit function. Just type exit.
