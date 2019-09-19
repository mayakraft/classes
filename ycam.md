# 🌸 garden mathematics 🌼

this class is a part of [SFPC at YCAM 2019](https://www.ycam.jp/events/2019/sfpc/).

This course aims to revisit mathematics, not necessarily introduce new math but in place of the traditional methods build a more personal language for expressing play, algorithmic thinking, computation and recursion. By re-thinking our heavy reliance on traditional notation we offer the potential for a radical new way of understanding math. In this class we especially highlight ways math is explored in origami, crafts, and code.

> "In many classrooms, students are not permitted to construct a personal understanding of the mathematics that is presented. The values, traditions, beliefs, language, and habits reflective of the culture of the students are ignored. In such situations, the ways that children might invent personally meaningful conceptualizations are not respected."
>
> Ubiratan d'ambrosio

# day 1

*materials: square origami paper (some puzzles might require A4 paper)*

the puzzles selected here don't require that the students have any experience in origami. the effect of this lesson is to experience measurement using the medium itself.

[source](https://www.amazon.com/Paper-Puzzle-Book-All-Need/dp/9813202416)

## 1. origami foundations: axioms

*materials: square origami paper*

every origami maneuver can be expressed by one of seven axioms. we will perform a folding sequence that creases one line for every one of the seven axioms.

[origami axioms](https://rabbitear.org/examples/axioms/)

### bonus: Maekawa-gami

an introduction to origami design would be a weeks-long course in itself. this exercise introduces one core concept: sticking to the Maekawa-gami 22.5° grid. students will squash a simple swivel fold and are asked to look for the 22.5° solutions.

## 2. number bases

This section explores ethnomathematics and the evolution of counting. Why does 1/3 look terrible as a decimal but 1/4 looks okay? The history (and persistence) of non-western counting systems, the introduction of zero, observations of our own number system, number morphs, cyclic patterns, and operative patterns. This segment concludes with a musical rhythm activity where students perform musical bases as counting beats, dividing measures into whole numbers, compare the utility of base-10 to some alternative number bases.

[source](http://www.dozenal.org/articles/db4a117.pdf)

## 3. functions

*materials: one laptop, no software required except for a web browser*

now we introduce functions, our tool to manipulate abstract numbers. compare traditional ways of representing functions in math class and graphs to representations in code (Javascript). Discuss the data-flow language (pure data) representation of a function, introduce variable types, and learn to separate functions like sine from their typical use in math into an abstract tool with inputs and outputs, learn to harness these tools for creative explorations in code. it doesn't matter what we scale a function by, it still has the character of the function.

coding exercise 1: make an airplane hover mid-screen, with a slight up-down-up-down motion.
coding exercise 2: make an arrow always point toward your mouse.
coding exercise 3: make a circle follow your mouse, easing into place.

# day 2

functions review: identity values

```
x + 0 = x;
x * 1 = x;
```

Introduce the concept of "identity values" (0 addition, 1 multiplication, identity matrix), and how we use numbers just nearby (1.01) when live-coding to explore the flexibility of a system. Review how we used "+ n" and "* n" in our code from last time.

## 4. algorithms

*materials: one long strip of paper per person. drawing paper and pens*

Survey the events leading up to al-khwarizmi's "الكتاب المختصر في حساب الجبر والمقابلة" (Calculation by Completion and Balancing), placeholder zeros and Indian numerals, the innovation of balancing equations, and the contemporary notion of algorithms. We take a deep look at the Voronoi algorithm, and by internalizing a program it's possible to draw a Voronoi graph.

The Voronoi algorithm and origami: the Voronoi graph requires a perpendicular bisector calculation, which is precisely origami axiom 2 (fold a point to a point), and time will be spent understanding how to anticipate which cells are neighbors thereby having a crease line between them.

source: [voronoi](http://orderinspace.blogspot.com/2015/07/voronoi.html)

## 5. logarithmic thinking

"what number is halfway between 1 and 9?" we discuss the work of Stanislas Dehaene how Logarithmic thinking is innate and unlearned. This conversation includes the logarithmic nature of human senses, audio and visual, and noise and compression, JPEG compression, the mathematical relationship between musical pitches. We explore logarithms by folding the Fibonacci sequence and deriving the golden ratio, and learning about the appearance of both in plants. We draw a graph and mark the axes labels logarithmically by hand, and plot the fibonacci sequence on our graph. n^x and log() can be used to convert between linear and logarithmic, we use these tools to code a visualization of the solar system and convert between systems.

## 6. recursion

Our final computing concept is recursion, defining a concept in terms of itself. Students are presented with the MU puzzle (Hofstadter) and given a chance to solve it. This leads to a discussion of string rewriting systems, grammars, recursion, finite automata, and the history of how the search to formalize mathematics was halted by a recursive decision problem.

We begin by first drawing then folding a dragon curve. L-systems were developed to model the fractal nature of plants. In our final exercise we code a string rewrite function, and supply it with the dragon curve ruleset. language, grammars, language tokens.

coding exercise 3: L-systems

source: [9 iteration dragon curve](https://www.instagram.com/p/BlUirtdno1b/)
source: [fold a dragon curve](https://www.cutoutfoldup.com/216-dragon-curve.php)

### books, sources

- Douglas Hofstadter, "Godel Escher Bach"
- R. Buckminster Fuller, "Critical Path"
- Paul Lockhart, "Measurement"
- Ilan Garibi, David Goodman, Yossi Elran, "The Paper Puzzle Book"
- [the Church-Turing Thesis](https://plato.stanford.edu/entries/church-turing/)
- Chris Bernhardt, "Turing's Vision"
- [3 blue 1 brown](https://www.youtube.com/watch?v=kYB8IZa5AuE)
