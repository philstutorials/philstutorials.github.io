---
layout: default
---

# DATA 601: Working with Data and Visualization (Fall 2018)

Drop-in help: Friday: 5:00pm-7:00pm (ICT 517)

## Some considerations on looking up available operations, their names, and parameters

When you're writing your own code in a jupyter notebook it's useful to develop your own heuristic for looking things up. From my experience I would start with a strategy something like this:

1. When you have **no idea** if you're looking for functionality provided by the python language or a part of some library:
 > Google your vague questions, use the information you gather in 2, 3, 4, or 5.

2. When you **know who provides** the functionality you're looking for (e.g.  python, matplotlib, pandas, etc) but you don't really know what it would be:
 > Skim the tutorial in the documentation.

3. When you **know who and what** you're looking for but can't remember the function name or parameters
 > Go to the documentation's tutorial or reference.

4. When you **know the name** of a function but can't remember the parameters:
 > `?data.function_name <CTRL>+<ENTER>` in your jupyter notebook or go to the documentation's reference page.

5. When you **want to remind yourself** of the available operations on a particular data structure:
  > `object. <TAB>`.

 
This strategy is motivated by the fact that information returned from a google search may be out of date.
In other words the version of software (python, anaconda, or the python related libraries) **you're** using is different than the version **they're** using at the time that generous stranger posted an answer in a Q&A community.
The details of parameters may be different in your version or some functions may be depreciated in your version and the developers of the language/libraries may have created a completely new way to do what you want that's simpler but wasn't available before.

For your first assignment you only need to refer to the python and matplotlib documentation:
* [Python 3.6.6 Documentation (see Tutorial, Library Reference, and Language Reference)](https://docs.python.org/3.6/index.html)
* [Matplotlib 2.2.3 (see User's Guide>Tutorials and The Matplotlib API)](https://matplotlib.org/contents.html)

