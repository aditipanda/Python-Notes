import seaborn as sns <br>
color = sns.color_palette() - This returns a list of colors or a continuous colormap defining a palette. <br>
sns.color_palette('pastel') - shows a list of pastel shades! try it out, gurl!! <br>

**Shell or Command Shell** - A command line interface to your computer. It can be used to: <br>
- start and stop processes that run programs <br>
- create and delete files and directories (a.k.a folders)  <br>
- set environment variables  <br>
- manage processes and process resources  <br>
- automate tasks.
- Windows - cmd, power shell, Unix - bash, MacOS - tcsh.

**IPython** - A powerful toolkit with an interactive python shell + a Jupyter Kernel.
- IPython kernel helps with displaying plots that are outputs of jupyter code cells. It is designed to work with matplotlib library.
- Before plotting anything, use the magic function %matplotlib to set up the inner workings of IPython with matplotlib.
- If we use the %matplotlib magic function without any parameter, then by default, the plot is shown using the default matplotlib backend - outside the notebook on a separate window.
- If we use %matplotlib inline, the plot is shown using the inline backend, which places it immediately below the code cell, and can be stored as part of the notebook document.
- Can be used to try out short sequences of commands.
- IPython interpreter can be launched by typing **ipython** on the command line. If on Anaconda, there might be a separate launcher.

**Jupyter notebook** is used for longer interactive analysis, and interactive development environments (IDEs) like Emacs or VSCode, are used for creating resuable python packages. 
- A browser-based GUI to the IPython shell + builds a rich set of dynamic display capabilities on it.
- Apart from Python/IPython statements, Jupyter notebooks allow formatted text, static and dynamic visualizations, mathematical equations, JavaScript widgets, etc.
- The notebooks open and run on a browser, but they first connect to a running Python process (called kernel) in order to execute code. This is done by running "jupyter lab" in the system shell, or starting a Jupyter notebook from Anaconda or a standalone installation.

**IPython/Jupyter both**, help in answering complicated questions:
- the ? character is used to explore documentation
- the ?? characters to explore source code
- the tab key for autocompletion.

**Magic functions!** <br>
%matplotlib inline - 
