---
layout: default
---

# DATA 601: Working with Data and Visualization (Fall 2018)

Drop-in help: Friday: 5:00pm-7:00pm (ICT 517)

## On the topic of looking up available operations, their names, and parameters

When you're writing your own code in a jupyter notebook it's useful to develop your own heuristic for looking things up. From my experience I would start with a strategy something like this:

1. When you have **no idea** if you're looking for functionality provided by the python language or a part of some library:
 > Google your vague questions then go to 2, 3, 4, or 5.

2. When you **know who provides** the functionality you're looking for (e.g.  python, matplotlib, pandas, etc) but you don't really know what it would be:
 > Skim the tutorial in the documentation.

3. When you **know who and what** you're looking for but can't remember the function name or parameters
 > Go to the documentation's tutorial or reference.

4. When you **know the name** of a function but can't remember the parameters:
 > `object.function_name <CTRL>+<ENTER>` in your jupyter notebook or go to the documentation's reference page.

5. When you **want to remind yourself** of the available operations on a particular data structure:
  > `object. <TAB>`.

 
This strategy is motivated by the fact that information returned from a google search may be out of date.
In other words the version of software (python, anaconda, or the python related libraries) **you're** using is different than the version **they're** using at the time that generous stranger posted an answer in a Q&A community (e.g. stackoverflow).
The most common differences between versions are function parameters and function deprecation when the developers of the language/libraries have created a completely new way to perform some action.

If you recently followed the anaconda installation instructions provided on D2L, for your first assignment, you only need to refer to the *latest* python and matplotlib documentation:
* [Python 3.6.6 Documentation (see Tutorial, Library Reference, and Language Reference)](https://docs.python.org/3.6/index.html)
* [Matplotlib 2.2.3 (see User's Guide>Tutorials and The Matplotlib API)](https://matplotlib.org/contents.html)

----
## All cells share a 'global' set of function definitions, (default and imported) libraries, and defined variables.
These things are not local to the cell; *there's no need to repeat library imports, function definitions, or global variable definitions each time you use them in different cells.*

## Printing values is not the same as returning a value in a function definition.
It's true that they can act similarly in the context of a jupyter notebook, i.e., they can both appear as printed output of a cell. That said, having a function return a value is a crucial step in setting up a function to be reused in arbitrary ways in the rest of your code. For example, suppose your function f1 returned the value 3 and f2 returned 2. Then in a seperate cell, executing `print(f1()**f2())` would be calling `print(3**2)`. This would not be possible if f1 and f2 printed their values instead of returned them.

## For readability and reuse of your own functions it's important to limit the number of global variables that your functions use.
The use of global variables create dependencies. Dependencies increase the complexity of reasoning about your code. Also the value of the global variables, at the time that you call your defined function in late code, might not be what you thought it was so your computation might be incorrect! This is the reason functions take arguments and return values.


## Use exactly 1 tab or 4 spaces for each level of indentation.
