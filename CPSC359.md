---
layout: default
---

# CPSC 359: Computing Machinery II (Fall 2018)

Tutorials: Tuesday, Thursday: 12:00pm-12:50pm (MS 252)

----

### September 18th and 20th:
This week we'll practice what you learned in last week's lectures. That means we will:

- Practice translating between three different representations of boolean functions, i.e.,
 > logic diagrams <--> algebra <--> truth tables.

- Practice minimizing the number of literals and terms in boolean functions using axioms and theorems of boolean algebra.

- Practice finding the complements of boolean functions using two methods, i.e.,
  * application of axioms and theorems, and
  * by the "shortcut method" (find the dual and complement each literal).

Please bring pencil and paper to work on practice problems.

----

### September 25th and 27th:
On Tuesday we will practice minimixing three and four variable Boolean functions using the map method.

On Thursday we will become familiar with the Logisim application.

----
### October 2nd and 4th:
On Tuesday we will apply the design process to a simple example.

On Thursday we will finish our assignments.

----

### October 9th and 11th:
On Tuesday we will build various latches in Logisim.

On Thursday we will create various flip-flops.

----

### October 16th and 18th:
On Tuesday we will analyze a clocked sequential circuit.

> Using a principled analysis process we discovered that the [sequential circuit](https://raw.githubusercontent.com/philstutorials/philstutorials.github.io/master/_data/analyze_this.circ "Logisim file. Save this to your computer.") outputs 1 after it's seen 4+, consecutive, inputs of 1. Otherwise it outputs 0.

On Thursday we will design and implement a sequential circuit as well as simplify a 5-variable boolean function with a k-map. Contruct the circuit inside this [logisim file](https://raw.githubusercontent.com/philstutorials/philstutorials.github.io/master/_data/build_counter.circ "Logisim file. Save this to your computer.") to see it in action.

----

### October 23rd and 25th:
On Tuesday we will simplify a 5-variable boolean function and finish the design and implementation of a 2-bit counter circuit.

> Here's a [link](https://raw.githubusercontent.com/philstutorials/philstutorials.github.io/master/_data/simple_counter_split.circ "Logisim file. Save this to your computer.") to my modularly constructed circuit connected to my fancy terminal.

On Thursday we will finish our assignments.
If you want to test your assignment solution with a fancy terminal then do the follow:
1. load [this file](https://raw.githubusercontent.com/philstutorials/philstutorials.github.io/master/_data/HW2_tester_lib.circ "Logisim file. Save this to your computer.") as a Logisim library in your own circuit file
2. copy the contents of main circuit in the HW2_tester_lib library in your own main circuit.
3. attach inputs, outputs, and clocks.
4. set tick frequency to 4Hz and enable ticks, play with enable and direction input.

----

### October 30th and November 1st:
On Tuesday we play with our dessert.

On Thursday we will compile an example program for the Pi. This program uses the mini UART pins.

> [Slides](https://slides.com/pathomas/cross-compilation#/)

----

### November 6th and November 8th:
Tuesday is hands on; we're programming LED lights connected to your Pi.
> [Slides](https://slides.com/pathomas/gpio-programming#/)

On Thursday we will build on what we did on Tuesday. We'll write a programs to make buttons control the LED lights.
> [Slides](https://slides.com/pathomas/gpio-programming-button)


