---
layout: default
---

# CPSC 359: Computing Machinery II (Winter 2019)

Tutorials:  
**T04** - Monday, Wednesday: 11:00am-11:50am (MS 252)  
**T03** - Tuesday, Thursday: 11:00am-11:50am (MS 252)


----

### Week of January 21st:
This week we'll practice what you learned in last week's lectures. That means we will:

### October 30th and November 1st:
On Tuesday we play with our dessert.

- Practice translating between three different representations of boolean expressions, i.e.,
 > logic (circuit) diagrams <--> algebraic expressions <--> truth tables.

- Practice minimizing the number of literals and terms in boolean expressions using axioms and theorems of boolean algebra.

- Practice finding the complements of boolean expressions using two methods, i.e.,
  * application of axioms and theorems, and
  * by the "shortcut method" (find the dual and complement each literal).

Please bring pencil and paper to work on practice problems.

Here is are all the maths you need to know for digital logic.

<center>
<img src="https://raw.githubusercontent.com/philstutorials/philstutorials.github.io/master/_data/postulates_theorems1.png " width="550"/>
</center>

This is what minterms and maxterms are:
<center>
<img src="https://raw.githubusercontent.com/philstutorials/philstutorials.github.io/master/_data/minmaxterms1.png " width="550"/>
</center>


----

### Week of January 28th:
During the first tutorial we will practice minimizing three and four variable Boolean functions using the map method.

The second tutorial is dedicated to familiarizing ourselves with Logisim. Your first two assignments will require that you use this.

This is what Karnaugh maps look like..

<center>
<div>
 <img src="https://raw.githubusercontent.com/philstutorials/philstutorials.github.io/master/_data/kmap2-1.png " width="350"/>
 <img src="https://raw.githubusercontent.com/philstutorials/philstutorials.github.io/master/_data/kmap3-1.png " width="450"/>
 <img src="https://raw.githubusercontent.com/philstutorials/philstutorials.github.io/master/_data/kmap4-1.png " width="550"/>
</div>
</center>

----

### Week of February 4th:
The first tutorial will be a comprehensive example of combination circuit design. It will parallel the steps needed in your assignment.
<center>
<div>
<img src="https://raw.githubusercontent.com/philstutorials/philstutorials.github.io/master/_data/codes.png " width="550"
/>
</div>
</center>

[Resulting circuit.](https://raw.githubusercontent.com/philstutorials/philstutorials.github.io/master/_data/combinational_codes.circ "Logisim file. Save this to your computer.")


The second tutorial is a work period dedicated to your first assignment. I'll be there roaming around and helping where I can.

----

### Week of February 11th:
This week we will flip-flop around logisim to build an understanding of memory primitives used in synchronous clocked circuits.

----

### Week of February 18th:
The first tutorial is concluding the analysis of [this sequential circuit](https://raw.githubusercontent.com/philstutorials/philstutorials.github.io/master/_data/analyze_this.circ "Logisim file. Save this to your computer.").

The second tutorial will be a synthesis example:
 > Create a clocked synchronous sequential circuit that implements a _normal_
 > two bit counter with a single enable input.  
 > A normal two bit counter cycles through outputing:
 > 00, 01, 10, 11.  
 > Try it first using D flip-flops. Then try it again with JK flip-flops.
 
[Link](https://raw.githubusercontent.com/philstutorials/philstutorials.github.io/master/_data/simple_counter_split.circ "Logisim file. Save this to your computer.") to a modularly constructed version of the circuit with D-type flip-flops.

----

### Week of March 4th:
The first tutorial might include finishing the synthesis example, doing a 5-variable k-map example, and doing more example questions.

The second tutorial is a work period dedicated to your second assignment. I'll be there roaming around and helping where I can.

----

### Week of March 11th:
In the first tutorial we play with our dessert <img src="https://raw.githubusercontent.com/philstutorials/philstutorials.github.io/master/_data/trollface.png " width="20"/>.

In the second tutorial I'll go over compiling an example program for the Pi. This program uses the mini UART pins.

> [Slides](https://slides.com/pathomas/cross-compilation)

----

### Week of March 18th:
The first tutorial is hands on; we're programming LED lights connected to our Pi.
> [Slides](https://slides.com/pathomas/gpio-programming)

In the second tutorial we will build on what we did Tuesday. We'll write a program to make buttons control the LED lights.
> [Slides](https://slides.com/pathomas/gpio-programming-button)

----

### Week of March 25th:
The first tutorial introduces the details of setting interrupts to be requested and serviced instantly.
> [Slides](https://slides.com/pathomas/gpio-programming-interrupts)

The second tutorial is a work period dedicated to your third assignment. I'll be there roaming around and helping where I can.

If you're interested in getting the bonus part of the assignment look [here](https://www.valvers.com/open-software/raspberry-pi/step04-bare-metal-programming-in-c-pt4/). You're are suppose to have the system timer trigger interrupts at regular intervals and then have the function called by the interrupt switch the LEDs ;)

----

### Week of April Fools:
The first tutorial will be entirely assignment demos. First come first, first serve. You can leave when you're done.

The second tutorial is about Super Nintendo controller programming!

<img src=https://raw.githubusercontent.com/philstutorials/philstutorials.github.io/master/_data/snes.gif " width="200"/>.
